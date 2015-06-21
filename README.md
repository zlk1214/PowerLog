# PowerLog
Log on the time and the environment temperature automatically when powering on your computer.

It has been compiled on Fedora 22 64bit.

Installation:
1.Unzip powerlog2.2.tar.bz2 to a folder.
2.Change the path of the folder on the first line in powerlog2.2.tar.bz2/autorun.sh. (Default: /home/octopus/Programs/powerlog)
3.Open powerlog2.2.tar.bz2/conn.h to set the MySQL Connection settings.
4.Open powerlog2.2.tar.bz2/UART.h to set the Serial Port settings. (By default, the program sends 0x83 when measuring the temperature and the device sends back 4 bits containing the temperature information from DS18B20.
5.Import database.sql to your MySQL server.
6.Make and run ./powerlog2 to test.
7.Set powerlog2.2.tar/autorun.sh to run automatically when powering on.

