# HTMLCSS-Form
# Basic Form

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project 2</title>
    <style>
        body{
            background-color: orange;
        }

        .form{
            text-align: center;
            margin: 90px auto;
            padding: 10px;
            font-size: 20px;

            
            
        }

        label{
            font-size: 25px;
            text-align: justify;
            margin-left: 20px;
            display: inline-block;
            width: 240px;
        }

        input[type='text']{
            padding: 7px;
            outline: none;
            display: inline-block;
            width: 200px;
        }

        input[type='password']{
            padding: 7px;
            outline: none;
            display: inline-block;
            width: 200px;
        }
        
        input[type='radio']{
            padding: 7px;
            outline: none;
            display: inline-block;
            width: 50px;
        }

        input[type='date']{
            display: inline-block;
            width: 210px;
        }

        input[type='checkbox']{
            display: inline-block;
            width: 10px;
            outline: none;
        }

        .w{

            width: 40px;
            height: 10px;


        }

        input[type='date']{
            outline: none;
        }

        textarea{
            outline: none;
        }

        input[type='submit']{
            
            padding: 10px;
            color: white;
            background-color: black;
            margin: 10px;
            border-radius: 10px;
            outline: none;
        }

        input[type='reset']{
            
            padding: 10px;
            color: white;
            background-color: black;
            margin: 10px;
            border-radius: 10px;
            outline: none;
        }

        

        
    </style>
</head>
<body>

    <div class="form">

        <label for="">UserName : </label>
        <input type="text"><br>
        <label for="">Phone Number : </label>
        <input type="text"><br>
        <label for="">Email Id</label>
        <input type="text"><br>
        <label for="">Password : </label>
        <input type="password"><br>
        <label for="">Gender : </label>
        <input type="radio" name="" id="">Male
        <input type="radio" name="" id="">Female<br>
        <label for="">DateOfBirth : </label>
        <input type="date"><br>
        

        <label for="">Hobbies : </label>
        <input type="checkbox" class="w">Singing
        <input type="checkbox" name="" id="" class="w">Dancing
        <input type="checkbox" class="w">Coding<br>

        <label for="">Address : </label>
        <textarea name="" id="" cols="40" rows="20"></textarea><br>

        <input type="submit">

        <input type="reset">

    </div>
    
</body>
</html>


