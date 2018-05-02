## 1(a). Explain the following architecture terms
### (i) Thin clients
It conducts a minimum processing on the client side.
Example, web browser.

### (ii) Fat clients
Fat clients carry more processing load. Used in traditional Client/Server model.
Example, desktop application, desktop game.

### (iii) Fat servers
Fat clients contain more application functionalities, provides more abstract, higher level functions. Client is often using a fast web browser.
Advantage: easier to manage, because when the system need to change, most of the change is done on the server side.

## 1(b) Explain the benefits of:
### (i) 2-tier client server model
- 2 tier usually means desktop application
- can be easily developed
- easy to maintain
- less complicated

### (ii) 3-tier architecture
- high scalable
- easier to distribute the application (e.g. via browser)
- application logic can be separted from UI logic
- higher overall  performance
- enhanced security
- platform independence
- higher data integrity (because app logic is separated from data-access logic)

## 1(c) Explain the value X and Y for the partition /dev/sdXY for both IDE and SCSI type disk.
??

## 1(d) 
- He haven't update the package index. He can update it by running `apt-get update`.
- The package he is trying to install does not exist in the repository.

## 2(a)(i)
Refer [here](https://www.cyberciti.biz/faq/what-is-a-routing-table/).
- Destination
- Gateway
- Genmask (Generality mask)
- Flags (U stands for UP, G means the route is to a gateway)
- MSS (Default maximum segment size for TCP connections over this route)
- Window (Default window size for TCP connections over this route)
- Ref (Number of references to this route)
- iface (which network interface)

## 2(a)(ii)
```
netstat -raN inet6
```

## 2(b)(i)
```
netstat -tuna
```

## 2(b)(ii)
```sh
-t # means to display TCP connections
-u # means to display UDP connections
-n # means to display the details in numeric
-a # means to display all details
```

## 2(c)(i)
Refer [here](https://www.swiftstack.com/docs/install/configure_networking.html).
```
auto eth0
iface eht0 inet static
    address 192.168.1.55
    netmask 255.255.255.0
    network 192.168.1.0
    gateway 192.168.1.254
```

## 2(c)(ii)  
```
auto eth0
iface ehto inet dhcp
```

## 3(a)
- IT related risk is increasing
- IT is complex
- IT is fast changing
- improving corporate governance
- improve management and control of IT activities
- organizations are relying more and more on IT technologies
    - managers need to know the critical risk of IT and whether they are being managed or not
- managements need to knows whether the infrastructure underpinning today's and tomorrow's IT (people,technology,process) supports the expected business needs

## 4(a)(i)
```
cat /etc/passwd
```

## 4(a)(ii)
```
cat /etc/passwd | grep simon
```

## 4(a)(iii)
```
userdel -r simon
```

## 4(a)(iv)
```
sudo usermod -aG adm,sudo wongjiahau
```

## 5(b)(i)
```
systemctl status apache2
```

## 5(b)(ii)
```
/etc/apache2/sites-available
```

## 5(c)(i)
```
chmod u+x testutar.sh
```

## 5(c)(ii)
```
chmod og+x testutar.sh
```

## 5(c)(iii)
```
chmod o-rws testutar.sh
```