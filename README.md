# Passgen (Password Generator For Python)

This is a Python package to generate a password easily in one line. You can use your projects for random fill during project development. 

## Installation
```python3  
    pip install pasgen
```

## Usage 
```python3 
from pasgen.core import pasgen
test = pasgen()
print(test)
```
## Parametres

### lenght (default = 7)
```python3
pasgen(length=10)
```
This parameter is the password length that you created.

### puncChars (default = False)
```python3
pasgen(puncChars=True)
```
This parameter adds punctuation characters.

### lowerCase (default = True)
```python3
pasgen(lowerCase=True)
```
This parameter adds lowercase characters.

### upperCase (default = True)
```python3
pasgen(upperCase=True)
```
This parameter adds uppercase characters.

### Base64(default = False)
```python3
pasgen(Base64=True)
```
This parameter encodes the password in base64.

### ROT13(default = False)
```python3
pasgen(ROT13=True)
```
This parameter encodes the password in ROT13.

### ROT47(default = False)
```python3
pasgen(ROT47=True)
```
This parameter encodes the password in ROT47.