# SQLi
### Altoromutual is a deliberately vulnerable web application designed for practicing SQL injection in a controlled environment.
![SQLi](https://github.com/user-attachments/assets/47d1c5a7-3c2a-4951-9c05-ed870c6485c7)

### Upon encountering a syntax error on Altoromutual, I identified a potential SQL injection vulnerability, as the error suggested improper handling of user input in SQL queries. This observation indicated that the application might be susceptible to SQL injection attacks, allowing for further exploration and exploitation.
![realizeditsvulernable2](https://github.com/user-attachments/assets/b48657b5-44b5-45a2-aff1-26dcf721aaa9)

### In my testing, I used SQL injection payloads like ' OR 1=1-- and ' OR '1'='1' -- to exploit the vulnerability and bypass authentication checks. By injecting these conditions, I manipulated the SQL query to always return true or comment out the rest of the query, which allowed me to gain unauthorized access.
![ACTUAlCODE2 3](https://github.com/user-attachments/assets/bd470ce1-ca3a-42b9-a4d3-399090768e6b)

#### Here is the result.
![insidethewebsite3](https://github.com/user-attachments/assets/8b40cc3c-e8ca-46d5-a8c6-0caef4b5eda2)
