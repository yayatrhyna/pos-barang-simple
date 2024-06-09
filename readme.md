## Deskripsi Aplikasi 
Source Code Aplikasi Penjualan Barang sederhana berbasis Website dengan PHP & MYSQL.

### * Untuk Reuploader Source Code tolong cantumin sumber juga ya, terima kasih :)

## Setting Koneksi PHP
setting koneksi di config.php dan ganti username, password dan dbname nya

## Penggunaan Login
Username : admin
<br/>
Password : 123
<br>
<span style="color:red">* Penggunaan Login untuk <b>single User</b> </span>

## Changelog
12 Desember 2022<br>
- Update v2.0
- Migrasi Template SB Admin 2 Bootstrap 4

31 Januari 2021<br>
- Tambah Sortir khusus stok kurang dari >= 3
- Cari Per Tanggal Laporan 
- Cari Per bulan Laporan
- Fix Perhitungan Laporan

06 Oktober 2020<br>
- revisi session error pada hosting dengan error : 
Warning: session_start(): Cannot send session cookie - headers already sent by (output started at [duplicate] -> fixed
- Ganti background login, header
- Ganti Header table barang, table keranjang, table laporan
- Fix transaksi -> transaksi stok < keranjang tidak bisa diproses
- penghapusan trigger sql
- penambahan fungsi transaksi untuk pengurangan stok barang setelah transaksi bayar 

23 Agustus 2020<br>
- revisi print
- menambahkan alert telah di bayar di bagian bayar transaksi penjualan

18 Juli 2020<br>
- fix edit kategori
- fix modal tambah barang
- rapihin form laporan

29 Agustus 2019 <br>
- laporan tampilan error  -> fixed
- klik button bayar transaksi  tidak masuk ke laporan -> fixed
- pencarian barang pada menu transaksi sudah otomatis dengan tambahan jquery ajax
- data laporan dapat dicari berdasarkan periode bulan dan tahun

<br>
** Jika ada issues atau revisi atau menambahkan fitur silahkan pull request di repository ini
