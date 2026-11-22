# Web/app học tập — Khoa học tự nhiên 7, Bài 37

**Bài 37: Ứng dụng sinh trưởng và phát triển ở sinh vật vào thực tiễn**
Môn Khoa học tự nhiên 7 — Chương IX: Sinh trưởng và phát triển ở sinh vật, Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Điều khiển sinh trưởng của cây: kéo 4 thanh trượt nhiệt độ, ánh sáng, nước, chất dinh dưỡng; cây SVG lớn dần và ra hoa khi mức sinh trưởng đạt 80% trở lên; 4 tình huống mẫu (nhà kính lí tưởng, mùa đông lạnh, hạn hán, bón thừa phân).
2. Cắt đứt vòng đời của muỗi: bấm vào từng giai đoạn (trứng, ấu trùng, nhộng, con trưởng thành) trên hình SVG; diệt muỗi hiệu quả nhất ở giai đoạn ấu trùng.

Đáp án trắc nghiệm: 1A 2C 3B 4A 5A 6A 7A 8C 9B 10B.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm tự động lưu về Google Sheets của giáo viên (qua Apps Script Web App, chạy bằng tài khoản giáo viên).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_KHTN7_Bai37.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script Web App nhận điểm trắc nghiệm, ghi vào Google Sheets (tab KetQua).
- `assets-flow/` — 3 ảnh nền (đăng nhập, nền chính, hero) + logo cá nhân của giáo viên.
