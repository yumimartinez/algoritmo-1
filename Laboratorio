#include <iostream> 
#include <conio.h> 
 
using namespace std; 
 
 
int digitos(int a) 
 { 
	int s=0; 
	while (a>0) 
 	{ a = a/10; 
 	  s++; 
 	} 
 	  return s; 
 	 
 } 
 
 
int sumadigito(int a) 
 { 
 	int c=0,d;  
 
 	while (a>0) 
 	{  
 	  d = a%10; 
 	  if( d%2!=0){ 
 	  c = c+d; 
 	  } 
 	a = a/10; 
 	} 
 
 	  return c; 
 } 
 
 
int orden(int a) 
{ 
 	int h=0,m; 
 	while(a>0) 
 	{ 
 		m = a%10; 
 		h = h*10+m; 
 		a = a/10; 
 	} 
 	return h; 
 } 
 
 
 int numerosimpares (int a) 
 { int b,w=0; 
 
 
 	while(a>0) 
 	{ b = a%10; 
 			if( b%2!=0) 
 			{ w = (w+b)*10; 
 
 
 			} 
 			a = a/10; 
 			 
 	} 
 	return w; 
 } 

 int main() 
 { 
	 int r,i,o,p,q,opcion,n;

	 cout<< "introduzca su numero por favor: "<< endl; 
 	cin>> n; 

 	if(n<=0){ 
 			cout << "ERROR!" << endl;
			cout << "Debe introducir un numero natural" << endl;
			cout << "Debe ser un numero entero mayor a 0" << endl;
	}


 	else { 
 	do{ 
 	cout<< "<<***** MENU *****>>"<< endl; 
 	cout<<" 1. Contar digitos"<< endl; 
 	cout<<" 2. Sumar digitos impares"<< endl; 
 	cout<<" 3. Ordenar numero al reves"<< endl; 
 	cout<<" 4. Numeros solo impares"<< endl; 
 	cout<<" 0.- SALIR"<< endl; 
 	cin>> opcion; 
 
 	switch (opcion) 
 	{ 

 
 	case 1:		r = digitos(n); 
 				cout << "El numero tiene " << r << " digitos" << endl; break; 
	case 2:		i = sumadigito(n); 
 				cout<< " La suma de los digitos impares es: "<< i << endl;break; 
 	case 3:		o = orden(n); 
 				cout<< "El nuemro invertido es: "<< o << endl;break; 
 	case 4:		p = numerosimpares(n); 
 				q = orden(p); 
 				cout<< "El numero es: " << q << endl; break; 
 	case 0:		cout<<" SALIR "<< endl; break; 	 
 	} 
 
  	} while(opcion !=0); 
 	} 
}
