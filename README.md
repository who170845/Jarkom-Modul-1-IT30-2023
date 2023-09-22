# Jarkom-Modul-1-IT30-2023

# Soal No.1
Awalnya saya mencari nama paket yang sekiranya mencurigakan, maka dari itu semua paket yang sekiranya memiliki nama mencurigakan saya coba satu-persatu. Ternyata beberapa paket aneh yang namanya sama. Namun ada satu paket yang berdiri sendiri yaitu GrabThePhiser, kemudian Sequence Number(raw) dan Aknowledgement Number(raw) ada di bagian kiri bawah, itu untuk menjawab poin a dan b. Kemudian untuk poin c dan d ada di paket yang berada di bawah paket GrabThePhiser. Kemudian akan muncul flag seperti di bawah.
![no 1](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/5a0dd28f-f331-41bb-8718-627696cebc18)

# Soal No.2
Untuk yang satu ini cukup gampang, tinggal klik kanan pada sembarang paket, kemudian klik Follow → http stream kemudian akan ditemukan Server bernama gunicorn seperti pada gambar di bawah.
![no 2ws](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/3c19876e-c54e-40ff-9697-5e7c52319d34)
Masukkan nama server tersebut, kemudian akan keluar flagnya.
![no 2tm](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/8da95c18-92fb-4431-95a7-bf73101d4849)

# Soal No.4
Langsung cari paket nomor 130. Kemudian cek satu-persatu di bagiankiri bawah, maka akan ditemukan Checksumnya.
![no 4ws](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/2af25ec4-9fc0-45bf-926b-6d636ec22c16)
Masukkan Checksum yang ditemukan, maka akan muncul flagnya.
![no 4tm](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/ace62c2c-ab2c-4444-9b09-873401bb71a3)

# Soal No.8
Disini saya mencari di google bagaimana filter port di wireshark, kemudian menemukan link https://linuxhint.com/filter_by_port_wireshark/. Saya coba satu-persatu contoh filter port yang ada di halaman web tersebut dan menemukan kueri udp.dstport == 67 || udp.dstport == 68, saya ubah angkanya menjadi 80, correct answer dan muncullah flagnya.
![no 8](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/9c04ced9-3583-4baf-806f-200ff1b65753)

# Soal No.10
Klik kolom protokol sekali sehingga setiap protokol kumpul sejenis, kemudian cari protokol TELNET. Klik kanan pada protokol TELNET, Lalu klik Follow → TCP Stream → scrol setiap stream hingga menemukan username dan password, uji coba setiap username dan password yang ada.
![no 10ws](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/92abded0-5b4e-44a9-9dbf-40c715b5f5c1)
Kemudian ditemukan bahwa dhafin:kesayangank0k0 adalah yang benar maka muncullah flagnya
![no 10tm](https://github.com/who170845/Jarkom-Modul-1-IT30-2023/assets/113872836/f3968adc-6110-41c5-9564-8d5a95dcba86)

Demikian Laporan praktikum dari klompok IT30, Sekian dan Terimakasih:-)




