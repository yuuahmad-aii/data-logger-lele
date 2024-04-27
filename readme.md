## perkenalan
ini adalah repo untuk program data logger kolam ikan yang nantinya akan me-log data dari sensor suhu dan ph kedalam microSD melalui modul microsd. cara penggunaannya cukup mudah, tinggal aktifkan alat, dan selesai.

untuk mendapatkan data logger hasil pembacaan sensor, ada dua cara yang bisa dilakukan 
- keluarkan sd card dan baca datanya
- komeksikan kontroller dengan smartphone atau laptop dan masuk ip berikut http://192.168.137.76/ 

## development process
### 27 april 2024
hari pertama membuat program
-buat program sederhana berupa web server yang dapat mengontrol led build-in pada nodemcu (gpio2)

<table>
  <tr>
    <td><img src="dokumentasi/gambar%20(1).png" alt="Gambar 1"></td>
    <td><img src="dokumentasi/gambar%20(2).png" alt="Gambar 2"></td>
  </tr>
    <tr>
    <td>gambar tampilan web server dari browser laptop</td>
    <td>gambar nama hotspot dan alamat ip untuk berkoneksi dengan nodemcu</td>
  </tr>
</table>
<!-- 
![gambar tampilan web server dari browser laptop](dokumentasi/gambar%20(1).png)
![gambar nama hotspot dan alamat ip untuk berkoneksi dengan nodemcu](dokumentasi/gambar%20(2).png) -->
