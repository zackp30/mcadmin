# Java installation

Usually you would have Java installed already (because the Minecraft client itself requires it, unless using the in-built JRE). But I shall walk you through this anyway.

## OpenJDK

OpenJDK is the open source implementation of Java.

1. Download the program: (all builds are from <https://github.com/alexkasko/openjdk-unofficial-builds#openjdk-unofficial-installers-for-windows-linux-and-mac-os-x> (thanks to him!))
  - Windows 32bit <https://bitbucket.org/alexkasko/openjdk-unofficial-builds/downloads/openjdk-1.7.0-u60-unofficial-windows-i586-installer.zip>
    - 32bit OpenJDK should work on both 32bit and 64bit, however, you cannot allocate more than 1GB of RAM to the MC instance if you use 32bit.
  - Windows 64bit <https://bitbucket.org/alexkasko/openjdk-unofficial-builds/downloads/openjdk-1.7.0-u60-unofficial-windows-amd64-installer.zip>
    - 64bit OpenJDK will work on **only** 64 bit windows. There are no memory limitations to my knowledge.
  - Linux 32bit <https://bitbucket.org/alexkasko/openjdk-unofficial-builds/downloads/openjdk-1.7.0-u60-unofficial-linux-i586-installer.zip>
    - 32bit OpenJDK should work on 32bit **only**, an you may not allocate more than 1GB to the Minecraft instances if 32bit is used.
  - Linux 64bit <https://bitbucket.org/alexkasko/openjdk-unofficial-builds/downloads/openjdk-1.7.0-u60-unofficial-linux-amd64-installer.zip>
    - 64bit OpenJDK should work on only 64bit, there are no memory limitations that I know of.
  - Mac OS X 64bit <https://bitbucket.org/alexkasko/openjdk-unofficial-builds/downloads/openjdk-1.7.0-u60-unofficial-macosx-x86_64-installer.zip>.
    - 64bit OpenJDK should work on only 64bit (32bit macs are unheard of nowadays), there are no memory limitations that I know of.
2. Extract the zip file and install using the file named `install` (or `install.exe` on Windows), by executing it (Windows: double click, Mac OS X: double click, Linux: `./install` within the terminal.)

## Oracle Java

Oracle Java (as I call it) is the closed-source implementation of Java, and is developed by Oracle who initially created Java.

## Differences

- OpenJDK and Oracle Java have virtually no differences[^1].

[^1]: See [this](http://stackoverflow.com/questions/22358071/differences-between-oracle-jdk-and-open-jdk-and-garbage-collection), [this](http://stackoverflow.com/questions/17360011/technically-what-is-the-main-difference-between-oracle-jdk-and-open-jdk), and [this](http://askubuntu.com/questions/437752/openjdk-oracle-is-better).
