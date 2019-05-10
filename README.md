# Lego Wedo 2.0 Motor Control

## Environment
- Linux
- Python 2.7 

## Installation

```
sudo apt-get update
sudo apt install libdbus-1-dev libudev-dev libical-dev libreadline-dev
sudo pip install gattlib
```

## Usage

If your Smart Hub's name is different, change the line:

```python
if name != '' and 'Smart Hub' in name:
```

Run the app with `gksudo`:

```
gksudo python app.py 
```

![Lego Wedo 2.0 motor control](https://www.codepool.biz/wp-content/uploads/2019/05/lego-wedo-motor-control.gif)

## Reference
- https://www.ev3dev.org/docs/tutorials/controlling-wedo2-motor/
- https://ofalcao.pt/blog/series/wedo-2-0-reverse-engineering