# LumaFix64
The LumaFix64 is not my design. 
This work is based on the brilliant work of Sven Peterson https://github.com/svenpetersen1965/LumaFix64
His version is based on <a href="https://www.lemon64.com/forum/viewtopic.php?t=40570&start=375">e5frog's LumaFix64 design</a>, which was released in March 7th, 2018 in the Lemon64.com forum. The changes in my design are:

* Added a VIC-II conversion to enable either shortboard or longboard voltages to the VIC-II, in order to be able to install 85xx VICs to an earlier (longboard) motherboard
* Added jumper to permit bypassing the C64 motherboard and push wires directly to the RF modulator unit (for aftermarker models that accepts it) in order to further reduce induced noise on the video lines

Sven advise that the Chroma potentiometer is not required but most LUMAFIX still includes it. If desired, it can be omitted, but this revision does not prepare solder points to do so, please use the potentiometer connections directly for that purpose. 

The LumaFix64 requires the precision round pin strips, because those are narrow enough not to break the socket of VIC-II chip. Since these pin strips are fragile, the LumaFix64 has to be handle with care.

Permission was initially received from e5frog for publishing these files, which was done in open hardware - the current development further enhance the design in pure open hardware ideology.
