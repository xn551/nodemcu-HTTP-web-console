# nodemcu-HTTP-web-console

[![Join the chat at https://gitter.im/nodemcu/nodemcu-firmware](https://img.shields.io/gitter/room/badges/shields.svg)](https://gitter.im/nodemcu/nodemcu-firmware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/nodemcu/nodemcu-firmware.svg)](https://travis-ci.org/nodemcu/nodemcu-firmware)
[![Documentation Status](https://img.shields.io/badge/docs-latest-yellow.svg?style=flat)](http://nodemcu.readthedocs.io/en/latest/)

This is a lua program based on nodemcu-firmware for ESP8266. By running this, You could debug your nodemcu on mobile phone with web browser.

The project contains four files. All of files is needed to upload into the nodmecu.
- `wf4.lua`, the web server executed on esp8266
- `form2.html`, the home-page of web server, using POST method, transform your command into webserver
- `print.txt`,  embeded in homepage, show the serial response message of nodemcu. 
- `favcion.ico`, the favicon of websever.

The interface is shown below:
  <img src="homepage.png"  />
