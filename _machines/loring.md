---
layout: single
permalink: /machines/loring/
title: "Loring"
excerpt: "S7/S15/S35/S70"
header:
  overlay_image: /assets/images/loring.jpg
  image: /assets/images/loring.jpg
  teaser: assets/images/loring.jpg
---
* __Producer:__ [Loring Smart Roast Inc](https://loring.com), USA
* __Machines:__ S7/S15/S35/S70
* __Connection:__ MODBUS TCP via the network
* __Features:__ 
  - logging of bean temperature (BT), return temperature (ET) and related rate-of-rise curves
  - logging of inlet temperature, stack temperature and gas level

**Watch out!** The computer running Artisan must be on the same IP network as the Loring roaster which usually is configured to have IP 192.168.1.199. Configure your computer to use a static IP address in the range 192.168.1.x (but with x different from that of the roaster which usually has 199), so for example 192.168.1.10, and set the subnet mask to 255.255.255.0. This can be done on Windows using the Network Sharing Center by adding a TCP/IPv4 Local Area Connection with those properties. On OS X you set your Ethernet port in the Network Control panel to "IPv4: Manually" and fill in the IP and subnet mask accordingly.
{: .notice--primary}