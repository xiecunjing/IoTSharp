# IoTSharp 

[![Build status](https://ci.appveyor.com/api/projects/status/5o23f5vss89ct2lw/branch/master?svg=true)](https://ci.appveyor.com/project/MaiKeBing/iotsharp/branch/master)
![GitHub](https://img.shields.io/github/license/iotsharp/iotsharp.svg)
![GitHub package.json version](https://img.shields.io/github/package-json/v/iotsharp/iotsharp-ui.svg?label=IoTSharp-UI%20Version)

IoTSharp is an open-source IoT platform for data collection, processing, visualization, and device management.



## Contributing
 - If you'd like to contribute to IoTSharp, please take a look at our [Contributing Guide](contributing.md).
 - If you have a question or have found a bug,[ file an issue.](https://github.com/IoTSharp/IoTSharp/issues)
 - To learn about project priorities as well as status and ship dates see the [IoTShap roadmap](roadmap.md).

## Support

 - [Stackoverflow](http://stackoverflow.com/questions/tagged/iotsharp)

## Documentation

## How to install

### Linux  
 -  mkdir  /var/iotsharp 
 -	cp ./*  /var/iotsharp/
 -	chmod 777 IoTSharp
 -	cp  iotsharp.service   /etc/systemd/system/iotsharp.service
 -	sudo systemctl enable  /etc/systemd/system/iotsharp.service 
 -	sudo systemctl start  iotsharp.service 
 -	sudo journalctl -fu  iotsharp.service 
 -	http://127.0.0.1:5000/ 

### Windows  
 - sc create iotsharp binPath= "D:\iotsharp\IoTSharp.exe" displayname= "IoTSharp"  start= auto

![IotSharp Logo](docs/images/iot_sharp_logo.png)
