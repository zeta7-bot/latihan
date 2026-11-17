# latihan

Menu latihan beban 10 menit, dua kali seminggu — satu halaman, jalan di HP, tanpa backend.

**Demo:** https://zeta7-bot.github.io/latihan/

## Isi program

Dua putaran, istirahat 60 detik antar set:

1. Goblet squat — 8 kg, 10 repetisi
2. Floor press — 8 kg, 10 repetisi per sisi
3. One-arm row — 8 kg, 10 repetisi per sisi
4. Romanian deadlift — 8 kg, 10 repetisi
5. Shoulder press — 4 kg, 10 repetisi
6. Plank — 30 detik

Total 12 set. Hari latihan: Senin dan Jumat. Selasa dan Kamis hari kantor (target langkah kaki), Rabu dan akhir pekan bebas.

## Fitur

- Panduan sesi langkah-per-langkah dengan timer istirahat 60 detik dan timer plank 30 detik
- Rincian set ("Set 3 / 12 · putaran 1") dan progress bar
- Riwayat sesi tersimpan di `localStorage` perangkat, tanpa dikirim ke mana pun
- Hitungan "sesi minggu ini: n / 2"
- Tanpa dependensi, tanpa CDN — jalan offline setelah halaman terbuka

## Keterbatasan

- Data tersimpan per perangkat dan per browser; tidak ada sinkronisasi antar perangkat
- Bukan pengganti program latihan bersertifikat; beban dan progresi bersifat saran umum
- Timer berjalan di tab aktif; kalau tab ditutup, sesi hilang

## Lisensi

MIT
