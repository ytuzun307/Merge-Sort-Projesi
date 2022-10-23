# Merge-Sort-Projesi
www.patika.dev

Proje 2
[16,21,11,8,12,22] -> Merge Sort

a)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
b)Big-O gösterimini yazınız.


a) Dizinin sağ ve sol dizi olarak yeniden yazılması	[16,21,11,8,12,22]
İki Eşit dizine bölünmesi	[16,21,11] - [8,12,22]
Sol ve sağdaki dizilerin tekrar ikiye bölünmesi	[16] - [21,11] - [8] - [12,22]
Tek eleman kalana kadar bir kez daha bölme	[16] - [21] - [11] - [8] - [12] - [22]
Sıralı bir şekilde aynı şekilde birleştirilmesi	[16] - [21,11] - [8] - [12,22]
Tekrar birleştirme	[11,16,21] - [8,12,22]
Dizinin elde edilmesi	[8,11,12,16,21,22]

b) Toplamda 6 işlem olması ve O(nlogn) gösteriminden dolayı O(6(log6)) şeklinde bir gösterimi olacaktır.
