Nama : WIWIT SETIAWAN
NIM : 311610743
Kelas :TI.18.C2
Tugas Praktikum Algoritma dan Pemrograman


	
Praktikum 3
latihan1: Program menampikan bilangan terbesar dari sejumlah bilangan acak yang di inputkan.
Jawab :
#include<iostream>

using namespace std;

int main() {
    int i=0;
    int max=0;
    int a,x;

    cout << "Masukkan jumlah bilangan: ";
    cin >> a;

    for (i;i<a;i++) {
        cout << "Masukkan bilangan ke-" << i+1 << ": ";
        cin >> x ;

        if (x > max)
        max = x;
    }

    cout << "Bilangan terbesar adalah: " << max << endl;
}


latihan2: Program menampilkan urutan bilangan dari yang terkecil sampai yang terbesar, dari 3 buah bilangan yang di inputkan.
Jawab :
#include<iostream>
using namespace std;

int main()
 {
    int A,B,C;
    cin >> A >> B >> C;
    if(A<B)
    {
        if(B<C)
            cout << A <<" "<<B <<" "<<C;
        else
        {
            if(A<C)
                cout << A <<" "<<C <<" "<<B;
          else
                cout << C <<" "<<A <<" "<<B;
         }
      }
      else
      {
         if(A<C)
             cout<< B <<" "<<A <<" "<<C;
       else
       {
           if(B<C)
               cout<< B <<" "<<C <<" "<<A;
            else
                cout<< C <<" "<<B <<" "<<A;
        }
}
}

latihan3: Sesuai dengan nim mahasiswa.
1. nim berakhiran ganjil: Program mencetak nilai tengah dari 3 buah bilangan yang di inputkan
Jawab :
#include<iostream>
using namespace std;

int main()
 {
    int A,B,C;
    cin >> A >> B >> C;
    if(A<B)
    {
        if(B<C)
            cout << A <<" "<<B <<" "<<C;
        else
        {
            if(A<C)
                cout << A <<" "<<C <<" "<<B;
          else
                cout << C <<" "<<A <<" "<<B;
         }
      }
      else
      {
         if(A<C)
             cout<< B <<" "<<A <<" "<<C;
       else
       {
           if(B<C)
               cout<< B <<" "<<C <<" "<<A;
            else
                cout<< C <<" "<<B <<" "<<A;
        }
}
}



