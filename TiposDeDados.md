# Tipos de dados

Tipos de dados que podem ser usados com SQL Server

## Categorias de tipo de dados

Os tipos de dados no SQL Server são organizados nas seguintes categorias:

* Numéricos exatos;
* Cadeias de caracteres Unicode;
* Numéricos aproximados;
* Cadeia de caracteres binária;
* Data e hora;
* Outros tipos de dados;
* Cadeias de caracteres;

### Numéricos exatos

| Tipos de Dados  	| Intervalo                                                               	    | Armazenamento 	|
|-----------------	|-------------------------------------------------------------------------	    |---------------	|
| bigint          	| -2^63 (-9.223.372.036.854.775.808) a 2^63-1 (9.223.372.036.854.775.807) 	    | 8 bytes       	|
| int             	| -2^31 (-2.147.483.648) a 2^31-1 (2.147.483.647)                         	    | 4 bytes       	|
| smallint        	| -2^15 (-32.768) a 2^15-1 (32.767)                                       	    | 2 bytes       	|
| tinyint         	| 0 a 255                                                                 	    | 1 byte        	|
| bits            	| Um tipo de dados inteiro que pode aceitar um valor 1,0 ou NULL          	    | ------        	|
| decimal         	| Tipo de dado numérico que têm precisão e escala fixa.                   	    |               	|
| numeric         	| Decimal e numeric são sinônimos e podem ser usados intercambiavelmente. 	    |               	|
| money           	| -922.337.203.685.477,5808 a 922.337.203.685.477,5807 (-922.337.203.685.477,58	| 8 bytes       	|
|                   | a 922.337.203.685.477,58 para o Informatica.                                  |-------            |
|                   | O Informatica dá suporte apenas a dois decimais, não quatro.)                 |-------            | 
| smallmoney      	| -214.748,3648 a 214.748,3647                                             	    | 4 bytes       	|

### Numéricos aproximados

____________________________________________________________________________________________________

Referencia:
https://learn.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver16