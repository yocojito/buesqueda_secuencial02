# buesqueda_secuencial02
tarea

#include <iostream>
#include<stdio.h>
#include<conio.h>

using namespace std;



int main()

{

        int a[8]={10,15,20,25,30,35,40,45};

        char b='F';

        int i, dato;        

        

        printf("Ingresa un numero a buscar en el arreglo: ");

        scanf("%i",&dato);

        

        i=0;

        while ((b=='F')&&(i<8)){

                if(a[i]>=dato){

                        b='V';

                        break;

                }

                i++;

                }

                if(b=='F'){

                cout<<"El numero no esta dentro del arreglo"<<endl;

                

        }

        

        else if (b=='V'){

                printf("El numero si existe en el arreglo en la posicion: %i", i-1);

        }

        

        getch();

        return 0;

}
