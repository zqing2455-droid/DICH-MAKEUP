# DỊCH MAKEUP — Sổ tay tra cứu & luyện thuật ngữ Trung–Việt

Web tra cứu và học thuật ngữ trang điểm Trung–Việt, dùng cho công việc **phiên dịch hiện trường lớp dạy trang điểm** (giảng viên Trung Quốc – học viên Việt Nam).

**→ Mở web: https://zqing2455-droid.github.io/DICH-MAKEUP/**

Một file `index.html` duy nhất, không cần cài gì, mở được offline, dùng tốt trên điện thoại.

## Có gì bên trong

| Mục | Nội dung |
|---|---|
| **Tra cứu** | 341 thuật ngữ, 13 nhóm. Gõ tiếng Trung, pinyin **không cần dấu**, hoặc tiếng Việt **không cần dấu** đều ra. |
| **Thẻ nhớ** | Lật thẻ hai chiều 中→Việt / Việt→中. Đánh dấu "thuộc rồi", tiến độ tự lưu trong máy. |
| **Kiểm tra** | Trắc nghiệm 12 câu, có chế độ *chỉ luyện từ bẫy*. Sai thì hiện luôn lời giải thích. |
| **Luyện dịch** | *Câu ngắn*: 96 câu hiện trường, hai chiều 中→Việt / Việt→中, dịch ra miệng rồi lật đáp án. *Đoạn dài*: 7 đoạn giảng viên nói thật (lớp nền · tạo khối · mắt · chân mày · hỏi đáp về da hai chiều · makeup lên ảnh), có đồng hồ bấm giờ, bản dịch tham khảo và phân tích chỗ khó. |
| **Mẫu câu** | 105 mẫu câu hiện trường, chia theo tình huống: chốt với giảng viên trước giờ học, khẩu lệnh thao tác, sửa lỗi, hỏi đáp hai chiều, câu cứu nguy khi bí. |
| **Kỹ năng** | Toàn bộ cẩm nang phiên dịch hiện trường, 6 mục mở gập: ba chế độ dịch trong một buổi · cách ghi chú + bộ ký hiệu riêng cho lớp makeup · xử lý tình huống hiện trường · 7 lỗi của người dịch lần đầu · kế hoạch luyện 4 tuần · **checklist ngày dạy tick được, tự lưu trong máy**. |
| **20 từ bẫy** | Nhóm từ vừa hay gặp nhất vừa dễ dịch sai nhất — học nhóm này trước. |

## Nguyên tắc biên soạn

Cột tiếng Việt ghi **cách dân trong nghề thực sự nói**, không phải bản dịch sát chữ. Học viên là người đang làm nghề: họ nói *kem lót*, *cushion*, *rãnh cười*, *mí lót* — không nói "kem cách ly", "đệm hơi", "nếp nhăn pháp lệnh".

Các từ có dấu ⚠ là chỗ dịch sát chữ sẽ sai nghĩa. Ví dụ:

- 服帖 → **bám da / ăn da** (không phải "phục dán")
- 面中 → **vùng giữa mặt** (dịch sai là học viên chỉ sai chỗ trên mặt)
- 山根 → **gốc mũi**, chỉ phần giữa hai mắt — không phải cả sống mũi
- 带一下 → **quét qua nhẹ một đường** (dịch chữ là sai hoàn toàn)
- 晕染 (tán — kỹ thuật tốt) ≠ 晕妆 (nhoè — lỗi): gần âm, nghĩa trái ngược

## Tài liệu đi kèm (bản Word)

1. Sổ tay thuật ngữ makeup Trung–Việt
2. Sổ tay mẫu câu hiện trường
3. Kỹ năng phiên dịch & kế hoạch luyện tập 4 tuần

## Cập nhật nội dung

Dữ liệu nằm ngay trong `index.html`, ở biến `const D = {...}` đầu thẻ `<script>`.

Thêm một thuật ngữ:

```js
{ i: 231, zh: "搓泥", py: "cuōní", vi: "sản phẩm bị vo cục",
  note: "Lưu ý khi dịch…", w: 1, c: "Hiệu ứng & lỗi", cz: "妆效" }
```

`w: 1` = từ bẫy (hiện nền cam, vào được chế độ luyện riêng). `c` phải trùng một trong các nhóm đã có.
