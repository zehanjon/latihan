# latihan modul 1
===================================/* File hello.c */
#include <stdio.h>

void main()
{
   printf("hello\n ");
}

===================================/* File : hello1.c */
/* menuliskan hello ke layar */
/* pola ini merupakan standard yang dipakai di kelas */
#include <stdio.h>

int main ()
{
/* KAMUS */
/* ALGORITMA */
    printf ("hello\n");
return 0;
}

===================================/* File : ASIGN.C */
/* Assignment nilai integer dan print */
#include <stdio.h>

int main ()
{
/* Kamus */
int i;

/* Program */
printf ("hello\n");
i = 5;
printf ("Ini nilai i : %d \n", i);
return 0;
}


=====================================/* File asgdll.c */
#include <stdio.h>

int main()
{ /* Kamus */
float f;
long double fll;
/* Algoritma */
f= 20.0f;
fll=10.0L;

printf("float f = %f \n", f);
printf("long double fll = %fl \n", fll);
return 0;
}

=====================================/* File : ASIGNi.C */
/* Assignement dan print */
#include <stdio.h>
#include <limits.h>
int
main ()
{
/* Kamus */
int i;
long int ii;
/* Program */
   printf ("hello\n\n");
   i = 1234;
  ii = 123456;
  printf ("Ini nilai i=1234 = : %d \n", i);
  printf ("Ini nilai ii=123456 : %10d \n\n", ii);
/* print nilai batas integer */
  printf ("Min dan Max integer : %d, %d \n", INT_MIN, INT_MAX);
  printf ("Max long integer : %ld, %ld \n", LONG_MAX);
return 0;
}

=====================================/*File : asign2.c */
/* Deskripsi :
/* Program ini berisi contoh sederhana untuk mendefinisikan
 variabel-variabel bilangan bulat (short int, int, long int),
 karakter, bilangan riil, */
#include <stdio.h>

int main ()
{
/* KAMUS */
short ks = 1;
int ki = 1;
long kl = 10000;
char c = 65;

/* inisialisasi karakter dengan integer */
char c1 = 'Z';

/* inisialisasi karakter dengan karakter */
float x = 1.55;

/* Algoritma */
/* penulisan karakter sebagai karakter */

printf ("Karakter = %c\n", c);
printf ("Karakter = %c\n", c1);

/* penulisan karakter sebagai integer */
printf ("Karakter = %d\n", c);
printf ("Karakter = %d\n", c1);
printf ("Bilangan integer (short) = %d\n", ks);
printf ("\t\t(int) = %d\n", ki);
printf ("\t\t(long) = %ld\n", kl);   /* perhatikan format %ld */
printf ("Bilangan Real = %f8.3\n", x);
return 0;
}

