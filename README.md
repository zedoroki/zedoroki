<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ŚЛО</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      text-align: center;
      background: url('https://i.imgur.com/uMI3b4z.png') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }
    h1 {
      margin-top: 20%;
      font-size: 3rem;
      text-shadow: 2px 2px 5px black;
    }
    form {
      margin-top: 20px;
    }
    textarea {
      width: 80%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
    }
    button {
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      background-color: #6c5ce7;
      color: white;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #341f97;
    }
  </style>
</head>
<body>
  <h1>اترك لي رسالة عبر البريد الإلكتروني!</h1>
  <form action="mailto:swwiswwi7@gmail.com" method="post" enctype="text/plain">
    <textarea name="message" rows="4" placeholder="اكتب رسالتك هنا..." required></textarea><br>
    <button type="submit">إرسال</button>
  </form>
</body>
</html>
