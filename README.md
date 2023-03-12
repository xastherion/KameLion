# KameLion

Is a "try to organize" that project from JavierIH in a new, easy an functional site.

Of course i find Kame-8dof over internet, but it´s a lot o unorganized information.

This is really because it scheint to be a programming freak people, but Kame is soooo nice, that is a beautiful project for parents the want to entusiasmate his children with tecnologie and robotic (my case)

First:
a bunch of 3d plastic is necesary. I find a good version in Thingiverse, from the original proyect from JavierIH. This parts are there, here in GibHub as JavierIH, and from p123ad too. Thanks a lot to both.

hier is the link to Javier .stl files:
https://www.thingiverse.com/thing:1265766

Another user corioco modified some parts to fix Tower Pro Sg90 servos, because a hole is missed (sg90 have one central hole)
https://www.thingiverse.com/thing:2827295

I find it to late, i think i make a aditional hole in this JavierLH model, but i recomend the corioco because sg90´s are cheaper.

Sergei do a nice remake of crabs-kame version
https://github.com/serg0000/fatKame/tree/serg_dev

and look like the programation is for arduino (my idee too)
i will try it before another improvements, because for the moment, i print and build the skelett.

The rasperry pi 2 version:
https://github.com/JavierIH/kame

Very funny TV-Show with JavierIH:
https://www.antena3.com/programas/el-hormiguero/secciones/ciencia-marron/kame-el-robot-impreso-en-3d-capaz-de-bailar-breakdance_201802215a8de6b70cf279b114c38345.html

A little explication about all versions:

KAME - Original(?) author JavierHL: a Raspery 2 + ESP wifi modul + Quality Motors

miniKAME

poorKAME - a good adaptation version for the cheaper SG90 servos motors, especially Body and Brackets because the motors screws holes (just one instead of two) 

p123ad/kame - very well CAD parts Documented version with diagrams and photos

fatKAME - a improved beatifull "Crabs" version of miniKAME with distance sensors and simple "obtacles avoid" funktion. The Control-Website offer 3 funktions more too.

poorKAME Punk (with voltage regulator):
https://www.youtube.com/watch?v=6CAGECC3nNk&t=6s
https://www.thingiverse.com/thing:1428651


-----------------------------------------------
KAME (original text from p123ad):
This is a 8DOF quadrupet robot controlled with ESP32 board.
Connection via Wifi and telnet protocol.

This build is based on the Project form [JavierIH](https://github.com/JavierIH/miniKame).
Some Parts are redesgined to fit a ESP32 Development board inside.

Here is a Picture of the finished Robot
<img src="/doc/images/kame_stand.jpg" width="45%"></img>

https://www.thingiverse.com/thing:3945903

https://github.com/manuel6662/kameqwerty

Board pins can be set to match this scheme in the function init of minikame library. Example:
````
board_pins[0] = D1; // Servo S0
board_pins[1] = D4; // Servo S1
board_pins[2] = D8; // Servo S2
board_pins[3] = D6; // Servo S3
board_pins[4] = D7; // Servo S4
board_pins[5] = D5; // Servo S5
board_pins[6] = D2; // Servo S6
board_pins[7] = D3; // Servo S7
````

## License
This project was build upon the great work from [JavierIH](https://github.com/JavierIH/miniKame)
