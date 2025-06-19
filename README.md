🧪 Thực hành Kiểm thử API với Postman

Ngày Kiểm Thử: 19/06/2025

Người Kiểm Thử: Đinh Trường Huy

🚀 Giới thiệu

🧰 GIỚI THIỆU VỀ POSTMAN
Postman là một công cụ mạnh mẽ được sử dụng rộng rãi trong phát triển và kiểm thử API (Application Programming Interface). Nó cung cấp một giao diện đồ họa trực quan giúp lập trình viên và kiểm thử viên dễ dàng gửi các yêu cầu HTTP và kiểm tra phản hồi từ máy chủ mà không cần viết mã phức tạp.

🔑 TÍNH NĂNG CHÍNH
Tính năng	Mô tả
Gửi các yêu cầu HTTP	Hỗ trợ các phương thức như GET, POST, PUT, DELETE,...
Tạo Collection	Tổ chức các API thành nhóm theo module/dự án
Quản lý Environment	Dễ dàng chuyển đổi giữa các môi trường (dev, test, production)
Kiểm thử tự động (Tests)	Viết script kiểm tra kết quả trả về từ API
Chia sẻ và cộng tác	Xuất/nhập API và làm việc nhóm dễ dàng
Mock Server	Giả lập API chưa xây dựng xong để kiểm thử sớm
Theo dõi lịch sử yêu cầu	Giúp xem lại các request đã thực hiện trước đó

🎯 LỢI ÍCH CỦA VIỆC DÙNG POSTMAN
Tiết kiệm thời gian trong kiểm thử API thủ công

Giảm lỗi do thao tác bằng tay

Dễ dàng kiểm thử cả API có bảo mật (token, OAuth,...)

Hỗ trợ tạo test script đơn giản bằng JavaScript

Thân thiện với người mới bắt đầu, không cần biết lập trình sâu
1. Mục Tiêu Kiểm Thử: Sử dụng Postman để kiểm thử một API thực tế

2. Môi Trường Kiểm Thử: Postman.

3. Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Postman.

4. Kịch Bản Kiểm Thử Lần 1:
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

4.1. Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts/1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/c9607907-7e3d-4ee9-828e-de5f4f803796)


Kết quả kiểm thử chi tiết:
{
    "userId": 1,
    "id": 1,
    "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
    "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}


4.2. Phương Thức HTTP (GET/POST/PUT/DELETE): POST

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts
Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/98201830-5d7e-47f7-851e-2987630d31a7)

Kết quả kiểm thử chi tiết:
{
    "id": 101
}

4.3. Phương Thức HTTP (GET/POST/PUT/DELETE): PUT

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts
Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/aff67bbf-db5a-4731-a5fd-2aaccf9476a3)


Kết quả kiểm thử chi tiết:
{}

4.4. Phương Thức HTTP (GET/POST/PUT/DELETE): DELETE 

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts/1
Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/07f796e5-baf9-4c4d-bffb-115f10658583)



Kết quả kiểm thử chi tiết:
{}







