# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
## Developed by : YOKESH H
## Reg no :212224230312
```
<html>
    <head>
    <title>Slot Time Table - YOKESH H  (212224230312)</title>
</head>
    <body>
        <center>
            <img src="logo.png" width="500">
        </center>
        <table border="1" cellpadding="10" align="center" bgcolor="cyan">
            <caption><h2>Slot Time-Table</h2></caption>
            <caption><h3>YOKESH H (212224230312)</h3></caption>
            <tr><th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th></tr>
            <tr><th>8-10</th><td bgcolor="red">Web</td><td>CN</td><td>DBMS</td></tr>
            <tr><th>10-12</th><td>Web</td><td>CN</td><td>DBMS</td></tr>
            <tr align="center"><th>12-1</th><td colspan="3">Lunch</td></tr>
            <tr><th>1-3</th><td>Web</td><td>CN</td><td>DBMS</td></tr>
            <tr><th>3-5</th><td>Web</td><td>CN</td><td>DBMS</td></tr>
        </table>
    </body>
</html>
```



## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
