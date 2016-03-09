# Pi-Somfy
A script to open and close your Somfy (and SIMU) blinds with a Raspberry and an RF emitter.

The script will use the ephem library and pigpiod daemon to open and close Somfy (or SIMU) blinds, depending the the time of sunrise and sunset.
The remote address and rolling code (incremented every time you send a frame) are store in a specific file for every remote.
