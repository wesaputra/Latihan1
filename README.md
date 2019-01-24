## latihan1

# Apa Itu GIT ?
![git-logo-1788c](https://user-images.githubusercontent.com/46749030/51702282-fb274d80-2045-11e9-8951-9a27f177f9ba.png)

  GIT adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. GIT dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database GIT tidak hanya berada dalam satu tempat saja.


# Cara Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:
1.	Buka https://gitforwindows.org/ dan download installer GIT untuk Windows.
2.	Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.


## Beberapa Perintah Pada GIT

  1.	*git init*, perintah untuk membuat repository local.
  2.	*git add*, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
  3.	*git commit*, perintah untuk menyimpan perubahan kedalam database git.
  4.	*git push* -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
  5.	*git clone [url]*, perintah untuk membuat working directory yang diambil dari repositry sever.
  6.	*git remote add origin [url]*, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).


## Langkah-Langkah Menggunakan GIT

1.	Klik kanan pada Desktop, Klik “Git Bash Here”

![1 bener](https://user-images.githubusercontent.com/46749030/51702285-fd89a780-2045-11e9-9ddb-3bff52edce89.jpg)

2.	Akan tampil command prompt seperti ini :

![2](https://user-images.githubusercontent.com/46749030/51700735-7850c380-2042-11e9-979e-3b46d121b9e9.jpg)

3.	Buka Drive yang ingin di pakai “cd /d”

![3](https://user-images.githubusercontent.com/46749030/51700748-7e46a480-2042-11e9-91c8-66cc31525f84.jpg)

4.	Buat directory “mkdir pemrograman1” 
 
![4](https://user-images.githubusercontent.com/46749030/51700789-93bbce80-2042-11e9-9643-ed21faba3d67.jpg)

5.	Buka directory Pemrograman1 dengan perintah cd pemrograman1
 
![5](https://user-images.githubusercontent.com/46749030/51700831-9f0efa00-2042-11e9-9501-a8abb9603117.jpg)

6.	Buat directory latihan1 dan buka directory latihan1 “mkdir latihan1”

![6](https://user-images.githubusercontent.com/46749030/51700833-a209ea80-2042-11e9-8317-08cf6f0088e3.jpg)

7.	Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
 
![7](https://user-images.githubusercontent.com/46749030/51700838-a3d3ae00-2042-11e9-891f-150c902015ae.jpg)

8.	Jalankan perintah git init untuk menjalankan repository local 

![8](https://user-images.githubusercontent.com/46749030/51700843-a59d7180-2042-11e9-92bc-300fa19eabca.jpg)

9.	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md 

![9](https://user-images.githubusercontent.com/46749030/51700846-a7ffcb80-2042-11e9-9da7-233e978b59cc.jpg)

10.	Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"

![10](https://user-images.githubusercontent.com/46749030/51700852-a9c98f00-2042-11e9-9c67-bc7d51c3690c.jpg)

11.	Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository 
 
![11](https://user-images.githubusercontent.com/46749030/51700860-ac2be900-2042-11e9-8907-6f05b454138d.jpg)

12.	Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user. 

![12](https://user-images.githubusercontent.com/46749030/51700863-adf5ac80-2042-11e9-8802-e9bf54fc3f40.jpg)

13.	Mengirim perubahan ke server dengan perintah git push -u origin master 

![13](https://user-images.githubusercontent.com/46749030/51700886-bf3eb900-2042-11e9-80ba-8bd3d55d82f8.jpg)

14.	Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut

![14 s](https://user-images.githubusercontent.com/46749030/51700892-c1087c80-2042-11e9-9ca9-93ea75c9e773.jpg)

15.	Buka drive D kemudian klik Pemograman1

![15](https://user-images.githubusercontent.com/46749030/51700894-c2d24000-2042-11e9-8ddf-42f3068ab396.jpg)

16.	Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad 

![16](https://user-images.githubusercontent.com/46749030/51700910-cb2a7b00-2042-11e9-93ec-900feeb374fe.jpg)

17.	Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
 
![17 a](https://user-images.githubusercontent.com/46749030/51700912-cd8cd500-2042-11e9-9754-f1364d67a482.jpg)
![17 b](https://user-images.githubusercontent.com/46749030/51700914-cf569880-2042-11e9-8a31-f7d61f4017e1.jpg)
![17 c](https://user-images.githubusercontent.com/46749030/51700923-d2ea1f80-2042-11e9-8dd7-51cbc06791a6.jpg)

18.	Kemuidan lihat perubahannya pada laman github.com 

![18](https://user-images.githubusercontent.com/46749030/51700927-d4b3e300-2042-11e9-8d53-f342c432361d.jpg)



![sekian](https://user-images.githubusercontent.com/46749030/51701664-7b4cb380-2044-11e9-927b-ca4d7ec4175d.jpg)

# WAHYU EKA SAPUTRA

# 311810030

# TI 18 B.1
