# Library micropython-rfid-rc522

[micropython-rfid-rc522](https://github.com/zahid1905/micropython-rfid-rc522) is a **MicroPython** library that manages  the RC522 reader 
(chip MFRC522) on MicroPython boards.

It is a porting of [rpico-rc522](https://github.com/Mik3Rizzo/rpico-rc522).


## Library structure

The library offers two handy objects:
- **RC522**: low level class that manages the RC522.
- **RC522Manager**: high level class to easily read/write data from/to the NFC tag.

There is also a collection of utils functions.


## Requirements and install

To install the library, simply copy the `micropython-rfid-rc522` folder in the `lib` directory of the Pico.


## Wiring

The wiring configuration must be changed via software.


## About

**Michele Rizzo**, *Master's Degree Computer Engineering student at University of Brescia*.

Feel free to contact me by [mail](mailto:m.rizzo006@studenti.unibs.it) or visit my [Github](https://github.com/Mik3Rizzo/).