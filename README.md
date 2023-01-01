# Termux XFCE <br>
I give you...Termux with a GUI! <br>
Termux does support a GUI (XFCE and LXQT mainly) <br>
XFCE being one of the most customisable and best DEs, I decided to make a script that can install XFCE on Termux without any modifications! <br>
# How to install? <br>
* Just run:
```
apt install wget -y && wget "https://raw.githubusercontent.com/hyperio546/termux-xfce/main/install.sh" && chmod +x install.sh && ./install.sh
``` 
and follow the steps! <br>
# How to access the GUI? <br>
Just install "VNC Viewer" from Play Store (or BVNC for advanced users) <br>
Type `localhost:1` in the connection, and then put the password you chose earlier and then login!
# How to start and stop the server <br>
`vncserver` to start <br>
`vncserver -kill :1` to stop <br><br>
# How do I make it look better?
* Run:
```
wget "https://raw.githubusercontent.com/hyperio546/termux-xfce/main/theme.sh" && chmod +x theme.sh && ./theme.sh
```
Which will install the following themes: <br>
- Orchis GTK theme
- Layan GTK theme
- Papirus icon theme
- Tela circle icon theme <br>
You should see a folder in the home directory called "themes-termux-xfce" which has the required files for the themes.
# Uninstallation
- Run: 
```
wget "https://raw.githubusercontent.com/hyperio546/termux-xfce/main/uninstall.sh" && chmod +x uninstall.sh && ./uninstall.sh
```
to undo all the changes done.
# Screenshots
<img src="pic1.jpg"> <br>
<img src="pic2.jpg">
<br>
<br>
Any issues are welcome for improvement!
