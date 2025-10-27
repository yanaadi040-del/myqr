# myqr
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://yanaadi040-del.github.io/myqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Ajhy QR Code Scanner" disabled=no dst-host=yanaadi040-del.github.io
```

### Powered 2025 by webqr.com
