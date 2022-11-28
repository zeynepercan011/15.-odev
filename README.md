# 15.-odev

//iki say�y� toplayan fonksiyon

#include<stdio.h>
int topla(int s1 , int s2);

int main(void)
{
	int s1,s2,sonuc;
	
printf("1. sayi: ");
scanf("%d" , &s1);

printf("2. sayi: ");
scanf("%d" , &s2);
	
	sonuc=topla(s1,s2);
	
	printf("toplam: %d" , sonuc);
	
	return 0;
}

int topla(int s1, int s2)
{
	return s1+s2;
}
