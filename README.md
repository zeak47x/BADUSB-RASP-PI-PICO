<h1>Bad USB - Raspberry Pi Pico</h1>


<h2>Description</h2>
This project transforms a Raspberry Pi Pico into a "Bad USB," a product popularized by Hak5's release of the "USB RubberDucky." The Raspberry Pi imitates a Human Interface Device (HID), such as a keyboard, and the computer recgonizes it as such. Then the Bad USB executes various commands the moment it is plugged in. It does so without the user's knowledge, and can extract sensitive information from the computer. On the other hand, the Bad USB could instead load and play funny videos that make the unsuspecting user laugh.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Circut Python</b>
- <b>Raspberry Pi Pico</b>
- <b>Micro-USB to USB-A</b>

<h2>Operating System </h2>

- <b>Windows 10-11</b>

<h2>Walk-through:</h2>

<p align="center">
Plug Raspberry Pi into PC: <br/>
<img src="https://i.imgur.com/th24D8a_d.jpeg?maxwidth=520&shape=thumb&fidelity=high" height="80%" width="80%" />
<br />
<br />
Download CircutPython and install on Pico:  <br/>
<img src="https://i.imgur.com/Ra5URfX_d.png?maxwidth=520&shape=thumb&fidelity=high" height="80%" width="80%" />
 <img src="https://i.imgur.com/0zjcmO4.png" height="80%" width="80%" />
<br />
<br />
Download adafruit-circuit-python-bundle-.6x-mpy-20210130.zip [HERE](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/tag/20210130): <br/>
<img src="https://i.imgur.com/p5Dr51D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Extract to another folder then click on libs and drag adafruit_hid onto Pico lib folder:  <br/>
<img src="https://i.imgur.com/jLUQRqd.png" height="80%" width="80%" />
 <img src="https://i.imgur.com/GZZ5Kmi.png" height="80%" width="80%" />
<br />
<br />
Dowwnload script from [HERE](https://github.com/dbisu/pico-ducky/blob/main/duckyinpython.py) Delete old code.py file. Then drag duckyinpython file onto Pico and rename to code.py:  <br/>
<img src="https://i.imgur.com/9AR5Tcp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download payloads and scripts from [HERE](https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads/library/prank):  <br/>
<img src="https://i.imgur.com/ZwKS2bh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To install script on Pico make a notepad file with your desired payload script. then save it as a .dd file. Drag the file onto the Pico and instantly unplug your Pico in order to prevent the payload from running on your system. This is for educational purposes only. Please use this responsbily.  <br/>
<img src=""/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
