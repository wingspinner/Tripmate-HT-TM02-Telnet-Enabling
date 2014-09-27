HooTooTM02
==========

Patches for HooToo TripMate TM0

These are not patches in the traditional sense. They are actually firmware upgrade files for the HooTooTM02 that change that removes the root password and enable the telnet server.

fw-WiFiPortTPatch-HooToo-TM02-2.000.016 only enables the telnet server

fw-WiFiPortPatch-HooToo-TM02-2.000.016 enables the telnet server and removes the root password

INSTRUCTIONS
============

Pretty simple.... simply use the factory method of upgrading the firmware using one of these images as the target.


NOTES
============

These upgrade images don't actually load anything into the TM02 - i.e. the firmware is not upgraded. They mearly modify the appropriate files in /etc to enable telnet and change the root password and then save the changes permanently so they won't disappear on the next reboot.

As with most stuff of this type there is risk it doesn't work on your device for any number of reasons. Therefore, you use this totally at your own risk. I developed this for my own purposes and they work for me but no guarantee it will work for you. If your TM02 is precious to you and you would be devastated it if bricked then best to just use the device as it comes from the factory and make modifications such as this.
