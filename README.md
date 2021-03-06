# simple-string-api

An experiment to get familiar with creating Golang APIs, and deals with string manipulation, as a means to get comfortable with using slices.

This project currently has 2 methods of string manipulation.

- reverse-string
- next-in-ascii
- previous-in-ascii

## 1. reverse-string
### 1.1. Summary
Returns a string in the JSON format, which is the reverse of the string passed to it.
### 1.2. Syntax
```http://localhost:12345/reverse-string/<string to parse>```
### 1.3. Example
```http://localhost:12345/reverse-string/gopher```

Returns the following JSON:

```{"reversedstring":"rehpog"}```

## 2. next-in-ascii
### 2.1. Summary
Returns a string in the JSON format, where each character returned is the next one on in the ASCII character set to the string passed to it.
### 2.2. Syntax
```http://localhost:12345/next-in-ascii/<string to parse>```
### 2.3. Example
```http://localhost:12345/next-in-ascii/gopher```

Returns the following JSON:

```{"nextinasciistring":"hpqifs"}```

## 3. previous-in-ascii
### 3.1. Summary
Returns a string in the JSON format, where each character returned is the previous one in the ASCII character set to the string passed to it.
### 3.2. Syntax
```http://localhost:12345/previous-in-ascii/<string to parse>```
### 3.3. Example
```http://localhost:12345/previous-in-ascii/gopher```

Returns the following JSON:

```{"previousinasciistring":"fnogdq"}```
