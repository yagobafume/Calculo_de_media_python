# Calculadora de média
### O objetivo do projeto é o calculo de média atravéz de notas de provas.

## Tecnologia Ultilizada:
- **Python** (3.13.2)

***
## Demonstração da execução;
```
def calcular_media(nota1, nota2):
    return(nota1 + nota2) / 2

print("=== Sistema de notas do aluno ===")
n1 = float(input("Digite a primeira nota:"))
n2 = float(input("Digite a segunda nota:"))

media = calcular_media(n1, n2)

print(f"A média final é: {media: .2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")

```
## Demonstração do Uso;

```
PS C:\Users\YAGONUNESBAFUME\Documents\aula_git_28> & "C:/Program Files/Python313/python.exe" c:/Users/YAGONUNESBAFUME/Documents/aula_git_28/app.py
=== Sistema de notas do aluno ===
Digite a primeira nota:8
Digite a segunda nota:6
A média final é:  7.00
Status: APROVADO!
```
### Autor: Yago Bafume 
#### Linkedln: www.linkedin.com/in/yagobafume