# Fastboot Driver telah terpasang di PC/Laptop kalian, jika tidak punya silahkan gunakan satu dari beberapa Fastboot Driver di bawah ini :
1. ADB Driver + Fastboot Driver (Minimal) Terbaru
2. ADB + Fastboot Driver Instant (Support hingga Android 9.0 Pie)
3. Android SDK Platform Tools (ADB + Fastboot Driver versi paling terbaru)
4. Download dan Install Asus Zenfone USB Driver di PC Windows kalian.
   Kabel USB
5. Asus Zenfone Max Pro M1 dengan kapasitas baterai lebih dari 50%
# Jika semua persyaratan terpenuhi penuhi, maka silahkan lanjut ke cara pemasangan TWRP tersebut
- Jika sudah rename file recovery yang telah kalian download tadi menjadi twrp.img lalu copy atau pindahkan file
  twrp.img kedalam folder direktori ABD dan Fastboot di PC kalian
- Silahkan masuk ke Mode Fastboot atau Mode Bootloader dengan cara menekan tombol Volume Up (+) dan Power berbarengan saat device kalian sudah dalam kondisi Power Off
- Koneksikan device kalian ke PC dengan USB dan buka aplikasi Command Promt (CMD) dan arah kan ke direktory driver ADB dan Fastboot kalian
-  Masukan perintah ini :(fastboot devices)
-  Jika sudah terkoneksi dengan baik silahkan masukan perintah ini : (fastboot flash recovery twrp.img)
-  Jika telah selesai masukan lagi perintah ini : (fastboot reboot)
# Done 
-  untuk bisa masuk ke Mode TWRP, kalian hanya perlu menekan tombol Volume Down (-) dan Power Berbarengan saat device kalin Power OFF, maka secara otomatis device kalian akan Booting ke Mode TWRP.

# warning 
- Penting ~ Jika terjadi Bootloop atau Brick setelah pemasangan TWRP tersebut, maka cara memperbaikinya ada di artikel ini Cara Atasi Bootloop Setelah Pasang TWRP Asus Zenfone Max Pro M1.
