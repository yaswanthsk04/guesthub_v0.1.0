Run this

Run this to set static ip
```
uci set network.lan.ipaddr='192.168.98.1'        # LAN Gateway IP
uci set network.lan.netmask='255.255.254.0'      # Subnet mask to allow 510 IPs
uci commit network
/etc/init.d/network restart
```

Init Script to Handle IP:
```
wget https://github.com/yaswanthsk04/guesthub_v0.1.0/raw/refs/heads/main/init-script.sh && chmod +x init-script.sh && ./init-script.sh
```

Setup up script to setup GuestHub:
```
wget https://github.com/yaswanthsk04/guesthub_v0.1.0/raw/refs/heads/main/setup-script.sh && chmod +x setup-script.sh && ./setup-script.sh
```
