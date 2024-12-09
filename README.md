
# **Demo1 - Hệ thống nhận diện và huấn luyện khuôn mặt**

Dự án này là một hệ thống nhận diện khuôn mặt sử dụng Haar Cascade và các module huấn luyện tùy chỉnh. Hệ thống có khả năng phát hiện khuôn mặt và huấn luyện mô hình để nhận diện chúng với độ chính xác cao.

## **Tính năng**

Nhận diện khuôn mặt: Sử dụng tệp haarcascade_frontalface_default.xml để phát hiện khuôn mặt trong hình ảnh hoặc video.
Huấn luyện tùy chỉnh: Bao gồm các tệp train1.py và train2.py để huấn luyện mô hình nhận diện khuôn mặt trên tập dữ liệu của bạn.
Quản lý tập dữ liệu: Tổ chức và sử dụng tập dữ liệu hiệu quả để huấn luyện mô hình.
Cấu hình linh hoạt: Dễ dàng thay đổi các thiết lập thông qua tệp setting.py.

## **Cấu trúc dự án**

-RUN.py: Tệp chính để chạy ứng dụng.  
-setting.py: Tệp cấu hình cho các thông số của hệ thống.  
-train1.py và train2.py: Tệp mã nguồn để huấn luyện mô hình nhận diện khuôn mặt.  
-dataset/: Thư mục chứa tập dữ liệu để huấn luyện và kiểm thử.  
-trainer/: Thư mục chứa các logic và dữ liệu liên quan đến huấn luyện.  
-haarcascade_frontalface_default.xml: Mô hình Haar Cascade đã được huấn luyện sẵn để phát hiện khuôn mặt.  

## **Hướng dẫn sử dụng**  
Cài đặt môi trường:  
> Để cài đặt các thư viện cần thiết, hãy chạy lệnh sau:
>
> ```bash
> pip install -r requirements.txt
> ```
  
Đảm bảo tập dữ liệu được tổ chức đúng cách trong thư mục dataset/.  

Chạy chương trình:  
Thực thi tệp chính:  
Chạy lệnh sau: `python RUN.py`

Huấn luyện mô hình:  
Sử dụng `train1.py` hoặc `train2.py` để huấn luyện mô hình với tập dữ liệu của bạn:  
`python train1.py`
