<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Congratulations!</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff; /* Light blue background */
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
            background-color: #fff; /* White background */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }
        .tulip {
            position: relative;
            width: 100px;
            height: 250px;
        }
        .stem {
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 20px;
            height: 200px;
            background-color: green;
            transform: translateX(-50%);
        }
        .leaf {
            position: absolute;
            bottom: 40px;
            width: 20px;
            height: 100px;
            background-color: green;
            border-radius: 20px 20px 0 0;
        }
        .leaf.right {
            left: 60px;
            transform: rotate(30deg);
        }
        .leaf.left {
            right: 60px;
            transform: rotate(-30deg);
        }
        .petal {
            position: absolute;
            bottom: 120px;
            width: 0;
            height: 0;
            border-left: 50px solid transparent;
            border-right: 50px solid transparent;
            border-bottom: 100px solid red;
            border-radius: 50% 50% 0 0;
        }
        .petal.middle {
            left: 0;
        }
        .petal.left {
            left: -50px;
            transform: rotate(-15deg);
        }
        .petal.right {
            left: 50px;
            transform: rotate(15deg);
        }
        .rainbow-text {
            font-size: 24px;
            background: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="rainbow-text">CONGRATULATIONS JOYCE ASTOR FOR PASSING GRADE 10 PROUD AKO SAYO TOL MISSYOU WHEN INOM</h1>
        <div class="tulip">
            <div class="stem"></div>
            <div class="leaf left"></div>
            <div class="leaf right"></div>
            <div class="petal middle"></div>
            <div class="petal left"></div>
            <div class="petal right"></div>
        </div>
    </div>
</body>
</html>
