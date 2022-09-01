# Graph-node

## Install
1. Clone repo to /opt/graph
   ```bash
   git clone https://github.com/AlloPay/graph-node.git /opt/graph
   ```
2. Install systemd service
   ```bash
   ln -s /opt/graph/graph.service /etc/systemd/system/graph.service
   systemctl enable graph
   ```


## Start
```bash
systemctl start graph
```


## Logs
```
journalctl -eu graph
```
