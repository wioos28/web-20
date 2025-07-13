<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <title>Nhận Coin</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; padding: 50px; }
    button {
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
      background-color: #4CAF50;
      border: none;
      color: white;
      border-radius: 8px;
    }
    #message { margin-top: 20px; font-size: 16px; }
  </style>
</head>
<body>
  <h1>Chào mừng bạn!</h1>
  <p>Nhấn nút bên dưới để nhận coin sau khi vượt link.</p>
  <button id="receiveCoinBtn">Nhận Coin</button>
  <div id="message"></div>

  <script>
    const btn = document.getElementById('receiveCoinBtn');
    const msg = document.getElementById('message');

    btn.addEventListener('click', () => {
      // Giả lập request gửi đến server để cộng coin
      // Thay bằng API thật nếu có

      btn.disabled = true;
      btn.textContent = 'Đang xử lý...';

      // Giả lập delay 1.5s
      setTimeout(() => {
        msg.textContent = '🎉 Bạn đã nhận được 100 coin thành công!';
        btn.textContent = 'Nhận Coin';
        btn.disabled = false;
      }, 1500);
    });
  </script>
</body>
</html>
