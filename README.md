# Kontribusi Pertama 

Melakukan suatu hal untuk pertama kali akan selalu terasa sulit. Terutama ketika berkolaborasi dan membuat kesalahan, akan menimbulkan rasa tidak nyaman. Namun, sumber terbuka adalah tentang berkolaborasi dan kerja sama. Kami ingin menyederhanakan cara kontributor sumber terbuka yang baru untuk mulai belajar dan berkontribusi untuk pertama kali.

Membaca artikel dan menonton tutorial memang dapat membantu, tetapi apa yang lebih baik dibandingkan dengan melakukannya langsung tanpa membuat kekacauan? Proyek ini bertujuan untuk menyediakan panduan dan menyederhanakan bagaimana para pemula dapat membuat kontribusi pertama mereka. Ingat: Semakin santai anda, maka semakin cepat anda belajar. Jika anda mencari cara untuk membuat kontribusi pertama maka cukup ikuti langkah-langkah berikut. Kami janji, ini akan menyenangkan.

Apabila belum memiliki git, [ install segera ]( https://help.github.com/articles/set-up-git/ ).

## 1. Fork repositori ini

Fork repositori ini dengan cara menekan tombol fork yang ada di bagian atas layar.
Hal tersebut akan membuat salinan repositori ini di akun anda.

## 2. Klon repositori

ekarang klon repositori ini ke komputer anda. Tekan tombol clone lalu tekan ikon "copy to clipboard".

Buka terminal dan eksekusi perintah git berikut:

```
git clone "url yang telah anda salin"
```
yang mana "url yang telah anda salin" (tanpa tanda petik) adalah url ke repositori ini. Lihat langkah sebelumnya untuk mendapatkan url.

Contoh:
```
git clone https://github.com/wrideveloper/Open-Hack-Day-2019.git
```
Dimana `username-anda` adalah username Github anda. Pada langkah ini anda menduplikasi konten dari repositori Open-Hack-Day-2019 di GitHub ke komputer anda.

## 3. Membuat Cabang

Ganti ke direktori repositori di komputer (jika belum ada di sana):

```
cd Open-Hack-Day-2019
```
Buat cabang dengan perintah `git checkout`:
```
git checkout -b <add-nama>
```

Contoh:
```
git checkout -b add-ikaru19
```
(Nama cabang tidak perlu mengandung kata *add* namun layak untuk ditambahkan karena tujuan dari cabang ini adalah menambahkan nama anda ke dalam sebuah daftar.)

## 4. Buat perubahan yang diperlukan lalu commit perubahan tersebut

Buka berkas `Contributors.md` menggunakan teks editor, tambahkan nama anda ke dalamnya lalu simpan berkas tersebut. Apabila anda masuk ke direktori dan mengeksekusi perintah `git status` maka anda dapat melihat bahwa telah ada perubahan. Tambahkan perubahan tersebut ke dalam cabang yang sebelumnya telah dibuat menggunakan perintah `git add`:
```
git add Contributors.md
```

Simpan perubahan tersebut menggunakan perintah `git commit`:
```
git commit -m "Add <nama> to Contributors list"
```
ganti `<nama>` dengan nama anda.


## 5. Dorong perubahan ke GitHub

Dorong perubahan menggunakan perintah `git push`:
```
git push origin <add-nama>
```
Ganti `<add-nama>` dengan nama cabang yang sebelumnya telah dibuat.

## 6. Submit perubahan untuk diulas

Jika anda membuka repositori anda di GitHub, maka akan ada tombol `Compare & pull request`. Tekan tombol tersebut.

Submit pull request.

Suatu saat nanti saya akan melakukan penggabungan terhadap semua perubahan anda ke cabang master proyek ini. Anda akan mendapatkan pemberitahuan melalui email setelah perubahan tersebut selesai digabungkan. eheh

Cabang master dari fork anda tidak akan memiliki perubahan-perubahan tersebut. Untuk membuat fork anda selaras dengan milik saya, ikuti langkah-langkah berikut.
