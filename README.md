```
curl -s https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
k3d cluster create tkb --servers 1 --agents 3 --image rancher/k3s:latest
```