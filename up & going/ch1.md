# You Don't Know JS: Up & Going
# Chương 1: Nhập môn Lập Trình

Chào mừng bạn đến với *You Don't Know JS* (*YDKJS*).

*Up & Going* là phần giới thiệu những khái niệm căn bản về nhập môn lập trình -- và tất nhiên chúng ta sẽ học về JavaScript (thường được viết tắt là JS) -- và cách chúng ta tiếp cận, hiểu rõ những phần khác của series sách này. Đặc biệt nếu bạn vừa mới tiếp cận với lập trình hoặc tìm hiểu về JavaScript, cuốn sách này sẽ giới thiệu tổng quát những điều bạn cần để bắt đầu cuộc hành trình (*up and going*).

Cuốn sách này bắt đầu bằng việc giải thích những khái niệm căn bản của lập trình ở mức cao. Nó thực sự dành cho những người mới bắt đầu tìm hiểu về *YDKJS* với rất ít hoặc không có kinh nghiệm lập trình, và đang tìm kiếm sự trợ giúp từ cuốn sách để giúp bạn bắt đầu cuộc hành trình dẫn tới sự hiểu biết về lập trình thông qua lăng kính của JavaScript.

Chương 1 nên được tiếp cận như một cách nhìn tổng quát về những điều bạn muốn học và thực hành để bạn thực sự đi vào thế giới lập trình. Ngoài ra còn có nhiều nguồn tài nguyên tuyệt vời khác để giúp bạn tìm hiểu sâu hơn về những chủ đề này, tôi khuyến khích bạn tìm hiểu thêm từ những nguồn đó như một sự bổ sung kiến thức vào chương sách này.

Một khi bạn cảm thấy thoải mái về những khái niệm căn bản, Chương 2 sẽ giúp bạn tìm hiểu về những hương vị quen thuộc của lập trình JavaScript. Chương 2 giới thiệu về JavaScript và một lần nữa xin nhấn mạnh rằng đó không phải là một hướng dẫn trọn vẹn -- cái mà những phần khác của *YDKJS* sẽ nói đến.

Nếu bạn đã khá thoải mái về JavaScript thì hãy bắt tay ngay vào từ chương 3 như một cách nhìn ngắn gọn về những gì bạn thật sự chờ đợi từ *YDKJS*

## Code

Hãy bắt đầu ngay từ những dòng đầu tiên.

Một chương trình, thường được gọi là một *source code* hay đơn giản chỉ là *code*, là một tập hợp các hướng dẫn đặc biệt để nói với máy tính thực thi những nhiệm vụ được giao. Thông thường thì code được lưu trữ trong các file văn bản, mặc dù với JavaScript, bạn có thể gõ code ngay trực tiếp trên giao diện developer của trình duyệt, chúng tôi sẽ giới thiệu đến trong thời gian ngắn tới.

Các quy tắc để định dạng và kết hợp các hướng dẫn lại với nhau gọi là  *computer language*, đôi khi được gọi là *syntax*, nó cũng tương tự như tiếng Anh cho bạn biết cách đánh vần từng từ và làm thế nào để tạo ra các câu có nghĩa bằng các từ vựng và dấu câu.


### Statements

Trong một ngôn ngữ máy tính, một nhóm các chữ cái, con số và operators thực hiện một nhiệm vụ nào đó được gọi là *statement*. Trong JavaScript, một *statement* nhìn giống như sau:

```js
a = b * 2;
```
Các ký tự `a` và `b` được gọi là *variables* (Xem thêm ở "Variables"), bạn có thể xem nó như là một cái hộp mà bạn có thể lưu trữ đồ vật trong đó. Trong lập trình, variables lưu trữ giá trị (ví dụ con số `42`), các giá trị này được sử dụng trong chương trình. Nghĩ về nó giống như là ký tự biểu tượng cho các giá trị của chính bản thân nó.

Ngược lại, `2` chỉ mang giá trị của chính nó, được gọi là *literal value*, vì nó đứng một mình và ko được lưu trữ trong một variable nào cả.

Các ký tự `=` và `*` gọi là các *operators*  (Xem thêm phần "Operators") -- Nó thực hiện các hoạt động liên quan tới giá trị và các variables ví dụ như là gán giá trị và tính toán toán học.

Đa phần các statements trong JavaScript được kết thúc bởi dấm chấm phẩy (`;`).

Statement `a = b * 2;` ra lệnh cho máy tính lấy giá trị hiện tại được lưu giữ trong variable `b`, rồi nhân nó với giá trị `2`, sau đó lưu trữ kết quả ngược trở lại vào một variable khác được gọi là `a`.

Chương trình máy tính thực ra chỉ là một tập hơp các statements, mà cùng với nhau chúng mô tả nên các bước để thực hiện mục đích của chương trình máy tính.


### Expressions

Những statments được tạo nên bởi một hoặc nhiều *expressions*. Một expression là một tham chiếu đến một variable hoặc một giá trị, hoặc một tập hợp các variable(s) và giá trị kết hợp với các operators.

Ví dụ:

```js
a = b * 2;
```
Statement này có 4 expressions:

* `2` là một *literal value expression*
* `b` là một *variable expression*, nghĩa là nó lấy giá trị hiện tại lưu trữ trong nó.
* `b * 2` là một *arithmetic expression*, nghĩa là nó thực hiện một phép nhân.
* `a = b * 2` là một *assignment expression*, nghĩa là nó gán kết quả của phép nhân `b * 2` cho variable `a` (chúng ta sẽ tìm hiểu thêm ở các bài tập sau).

Một expression đứng riêng một mình nó thì được gọi là một *expression statement*, như ví dụ sau:

```js
b * 2;
```

Cách viết này thường không phổ biến và hữu dụng, thông thường nó sẽ không ảnh hưởng gì đến hoạt động của chương trình -- nó nhận giá trị lưu trữ trong `b` và nhân giá trị đó với `2`, nhưng sau đó nó không làm gì với kết quả trả lại.

Một expression thường gặp hơn gọi là *call expression* (Xem thêm mục "Functions"), toàn bộ expression là một function gọi đến chính nó:

```js
alert( a );
```

### Thực hiện một Chương trình

Làm thế nào để một tập hợp những statements trong một chương trình có thể ra lệnh cho máy tính? Chương trình cần được thực hiện hay còn gọi là chạy chương trình (*executed* hoặc là *running the program*)

Statement được viết như là `a = b * 2` rất hữu dụng cho các lập trình viên vì họ có thể đọc và viết nó, nhưng nó không phải là cách mà máy tính có thể hiểu được. Vì vậy, một tiện ích đặc biệt trên máy tính gọi là thông dịch hoặc biên dịch (*interpreter* hoặc *compiler*) được dùng để dịch các đoạn mã bạn viết thành các câu lệnh mà máy tính có thể hiểu được.

Thông dịch *interpreter*: Với một số ngôn ngữ máy tính, thông dịch là cách dịch tuần tự các dòng lệnh từ trên xuống dưới, từng dòng một, mỗi khi chương trình được chạy.

Biên dịch *compiler*: Với một số ngôn ngữ máy tính khác, biên dịch là cách mà các dòng lệnh được dịch trước, sau đó khi chương trình chạy, thực ra máy tính chỉ chạy lại bản dịch đã có sẵn.

JavaScript thường được hiểu là một ngôn ngữ thông dịch *interpreted*, bởi vì mã nguồn JavaScript được xử lý mỗi khi nó được chạy. Nhưng điều đó không hoàn toàn chính xác. Các engines của JavaScript thực ra đã biên dịch toàn bộ chương trình và khi chương trình chạy, nó thực ra chạy trên những đoạn mã đã được biên dịch trước.

**Note:** Để tìm hiểu thêm thông tin về biên dịch JavaScript, xem thêm 2 chương đầu của cuốn *Scope & Closures*

## Try It Yourself

Chương này sẽ giới thiệu từng khái niệm lập trình bằng các đoạn mã đơn giản, tất nhiên được viết bằng JavaScript :)

Cần phải nhấn mạnh rằng: khi bạn học qua chương này -- bạn cần phải dành thời gian học đi học lại nhiều lần -- bạn cần phải thực hành các khái niệm được học bằng cách tự mình gõ lại những đoạn code được học. Cách dễ nhất để gõ những đoạn code là mở giao diện developer tools tích hợp sẵn trong các trình duyệt (Firefox, Chrome, IE, etc.).

**Tip:** Thông thường, bạn có thể khởi động giao diện developers tools bằng các phím tắt hoặc từ các menu. Để biết thêm thông tin chi tiết về việc kích hoạt và sử dụng các giao diện này, xin xem thêm ở đây: "Mastering The Developer Tools Console" (http://blog.teamtreehouse.com/mastering-developer-tools-console). Để có thể gõ cùng lúc nhiều dòng lệnh vào giao diện, bạn dùng `<shift> + <enter>` để sang dòng. Khi bạn gõ `<enter>` một mình, giao diện sẽ hiểu là bạn muốn chạy tất cả mọi thứ bạn vừa gõ.

Nào hãy cùng làm quen với quá trình chạy code trong giao diện điều khiển. Đầu tiên, tôi muốn bạn mở một tab trống trong trình duyệt của bạn. Tôi thường hay gõ `about:blank` vào thanh địa chỉ. Sau đó, đảm bảo rằng giao diện developer của bạn đã được mở, như chúng ta đã nói ở trên.

Còn bây giờ thì gõ những dòng code sau và xem chúng sẽ chạy thế nào:

```js
a = 21;

b = a * 2;

console.log( b );
```

Nếu bạn gõ những dòng lệnh đó vào trong console của Chrome nó sẽ hiện lên như sau:

<img src="fig1.png" width="500">


Go on, try it. Cách tốt nhất để học lập trình là bắt đầu coding.

### Output

Trong đoạn mã phía trên, chúng ta sử dụng `console.log(..)`. Tóm lại, hãy cùng nhìn xem đoạn mã đó nói cái gì?  

Bạn có thể đã đoán ra, nhưng đó chính xác là cách chúng ta in ra một đoạn văn bản (được hiểu là *output* cho người sử dụng) trong giao diện developer. Có 2 đặc điểm của statement đó mà chúng ra sẽ cùng giải thích.

Đầu tiên, dòng `log(b)` là một phần của một function (Xem thêm "Function"). Điều thực sự xảy ra đó là chúng ta bàn giao variable `b` cho function, và yêu cầu nó in ra màn hình giao diện.

Thứ hai, phần `console.` là một object nơi lưu trữ function `log(..)`. Chúng ta sẽ tìm hiểu thêm về objects và các properties trong Chương 2.

Một cách khác để tạo nên một output là bạn chạy statement `alert(..)`. Ví dụ như:

```js
alert( b );
```
Nếu bạn chạy dòng lệnh đó, bạn sẽ thấy là thay vì in ra giao diện điều khiển, nó sẽ nhảy ra một popup "Ok" với nội dung của variable `b`. Tuy nhiên, sử dụng `console.log(..)` thường sẽ làm cho việc học và chạy các chương trình đơn giản hơn là sử dụng `alert(..)`, vì bạn có thể output ra nhiều giá trị cùng lúc mà không làm gián đoạn giao diện của trình duyệt.

Trong cuống sách này, chúng ta sẽ sử dụng `console.log(..)` cho các ouput.

### Input

Trong khi chúng ta tìm hiểu về output, bạn có thể tự hỏi về *input* (tức là tiếp nhận thông tin từ người dùng).

Cách phổ biến nhất để nhận input là một trang HTML có chứa các form elements (ví dụ như hộp thoại - text boxes) để người dùng có thể nhập dữ liệu vào, và sau đó dùng JS để đọc các giá trị đó vào trong các variables của chương trình.

Nhưng có một cách dễ hơn để nhận input cho mục đích học tập và trình diễn đơn giản như những gì bạn sẽ làm trong suốt cuốn sách này. Đó là sử dụng `prompt(..)` function:

```js
age = prompt( "Please tell me your age:" );

console.log( age );
```
Có thể bạn cũng đoán ra được, thông điệp bạn gõ vào `prompt(..)` -- ở đây là dòng `"Please tell me your age:"` -- sẽ được in ra trong một popup.

Nó trông giống như sau:

<img src="fig2.png" width="500">

Sau khi bạn gửi đoạn văn bản input đó đi bằng cách click "OK", bạn sẽ nhận thấy rằng giá trị mà bạn nhập vào sẽ được lưu trữ trong variable `age`, và được *output* trong `console.log(..)`:

<img src="fig3.png" width="500">

Để giữ cho mọi thứ đơn giản trong quá trình chúng ta học những điều cản bản nhất của lập trình, những ví dụ trong cuốn sách này sẽ không yêu cầu input. Nhưng từ giờ bạn chắc đã hiểu cách dùng của `prompt(..)`, và nếu bạn muốn thử thách bản thân mình, bạn có thể sử dụng nó để input trong những ví dụ tìm tòi của bạn.  

## Operators

Operators là cách chúng ta thực hiện các thao tác trên variables và giá trị. Chúng ta đã thấy 2 ví dụ về JavaScript operators, đó là `=` và `*`.

Operator `*` thực hiện phép nhân toán học, quá đơn giản, phải không? :)

Operator `=` được sử dụng để gán giá trị *assignment* -- đầu tiên chúng ta tính toán giá trị bên vế phải của `=` (giá trị nguồn) và sau đó đặt nó vào trong variable được chỉ định bên vế trái (variable mục tiêu)


**Warning:** Điều này nhìn qua giống như đảo ngược thứ tự thông thường. Thay vì `a = 42`, một số người thích lật lại thứ tự bằng cách cho giá trị nguồn sang bên trái và đặt variable mục tiêu sang vế phải, giống như là `42 -> a` (Điều này không hợp lệ trong JavaScript). Thật không may là cách đặt `a = 42`, và các biến thể tương tự, là khá phổ biến trong các ngôn ngữ lập trình hiện đại. Nếu bạn cảm thấy không tự nhiên, xin dành một chút thời gian làm quen với nó.   

Xem xét:

```js
a = 2;
b = a + 1;
```
Ở đây chúng ta gán giá trị `2` cho variable `a`. Sau đó chúng ta lấy giá trị của variable `a` (vẫn là `2` thôi), và thêm `1` vào nó để dẫn đến giá trị `3`, sau đó lưu trữ giá trị đó trong variable `b`.

Bạn cần có từ khoá `var` trong các chương trình của mình, nó như là cách chính thống để khai báo (hoặc tạo ra) các *variables* (Xem thêm mục "Variables").

Bạn nên khai báo các variable bằng tên trước khi bạn sử dụng nó. Tuy nhiên bạn chỉ cần khai báo 1 variable một lần duy nhất trong 1 *scope* (Xem thêm "Scope"), và sau đó bạn có thể sử dụng nó bao nhiêu lần tuỳ bạn. Ví dụ:  

```js
var a = 20;

a = a + 1;
a = a * 2;

console.log( a );	// 42
```

Sau đây là các operators thông thường trong JavaScript:

* Gán giá trị: `=` như trong `a = 2`.
* Phép toán: `+` (Cộng), `-` (Trừ), `*` (Nhân), and `/` (Chia), như trong `a * 3`.
* Gán giá trị hỗn hợp: `+=`, `-=`, `*=`, và `/=` là các phép gán giá trị hỗn hợp được tạo thành từ một phép toán với một phép gán giá trị, như trong `a += 2` (giống với `a = a + 2`).
* Tăng/Giảm: `++` (tăng), `--` (giảm), như trong `a++` (tương tự với `a = a + 1`).
* Truy cập đến Object Property: `.` trong `console.log()`.

   Objects là các giá trị giữ các giá trị khác bằng một cái tên với địa chỉ cụ thể, gọi là properties. `obj.a` có nghĩa là một object gọi là `obj` có chứa một property có tên là `a`.
   Properties có thể được truy cập bằng cách gọi `obj["a"]`. Xem thêm Chương 2

* Phép cân bằng Equality: `==` (loose-equals), `===` (strict-equals), `!=` (loose not-equals), `!==` (strict not-equals), như trong `a == b`.

   Xem thêm "Values & Types" và Chương 2.
* So sánh: `<` (bé hơn), `>` (lớn hơn), `<=` (bé hơn hay còn gọi là loose-equals), `>=` (lớn hơn hay còn gọi là loose-equals), như trong `a <= b`.

  Xem thêm "Values & Types" và Chương 2.
* Biến logic Logical: `&&` (Và), `||` (Hoặc), như trong `a || b` có nghĩa là chọn `a` hoặc `b`.

   Những operators này được sử dụng để diễn tả điều kiện hỗn hợp (Xem thêm "Conditionals"), giống như là `a` hoặc `b` đúng thì cả điều kiện sẽ đúng.

**Note:** Tìm hiểu thêm về các operators ở trên, theo link sau: Mozilla Developer Network (MDN)'s "Expressions and Operators" (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators).

## Values & Types

Nếu bạn hỏi một nhân viên ở cửa hàng điện thoại về giá tiền của một chiếc điện thoại, họ sẽ nói là "Chín chín chấm chín chín" ($99.99), họ đang đưa cho bạn một con số cụ thể đại diện cho giá tiền bạn phải trả (cộng thuế) để mua nó. Nếu bạn muốn mua 2 cái, bạn có thể tính nhẩm số tiền bạn phải trả là $199.98.

Nếu cũng là người nhân viên đó đưa cho bạn một chiếc điện thoại khác và bảo bạn là "free" (Tất nhiên là trong ngoặc kép :)), họ không đưa cho bạn một con số cụ thể, mà thực ra họ đưa một cách hiểu khác cho cái giá bạn thực trả ($0.00) -- của từ "free".

Nếu sau đó bạn hỏi lại là chiếc điện thoại có đi kèm theo chân sạc không? Thì câu trả lời chỉ có thể là "có" hoặc "không".

Trong cách hiểu tương tự, khi bạn thể hiện các giá trị trong một chương trình, bạn chọn các đại diện khác nhau cho các giá trị dựa trên những gì bạn dự định làm với chúng.

Những đại diện khác nhau cho các giá trị này được gọi là các *types* trong ngôn ngữ lập trình. Trong JavaScript đã xây dựng sẵn các types nguyên thuỷ:

* Khi thực hiện các phép toán, bạn sử dụng các con số - `number`.
* Khi bạn muốn in ra các giá trị trên màn hình, bạn cần các chuỗi `string` (Một hoặc nhiều các ký tự, chữ cái, hoặc các câu).
* Khi bạn cần đưa ra các quyết định, bạn cần các kiểu `boolean` (`true` hoặc `false`).

Các giá trị bao gồm trực tiếp trong các mã nguồn được gọi là các *literals*. Kiểu `string` được bao quanh bởi ngoặc kép `"..."` hoặc ngoặc đơn (`'...'`) - Sự khác biệt duy nhất là phong cách ưu thích của từng người. Các kiểu `number` and `boolean` chỉ đại diện cho chính nó (ví dụ: `42`, `true`, ...).

Xem xét:

```js
"I am a string";
'I am also a string';

42;

true;
false;
```


Ngoài các kiểu `string`/`number`/`boolean`, các ngôn ngữ lập trình còn cung cấp phổ biến các kiểu *arrays*, *objects*, *functions*, và nhiều hơn nữa. Chúng ta sẽ tìm hiểu về các kiểu và giá trị này trong các phần sau.

### Chuyển đổi giữa các Types khác nhau

Nếu bạn có một `number` nhưng bạn cần in nó ra trên màn hình, bạn cần phải chuyển đổi giá trị đó thành một `string`, và trong JavaScript, việc chuyển đổi này được gọi là 'coercion'. Tương tự như vậy, nếu một người nào đó nhập một loạt các ký tự số vào một form của một trang ecommerce, thì đó là một `string`, nhưng nếu bạn muốn sử dụng giá trị của nó để làm các tính toán toán học thì bạn cần phải *coerce* nó thành một `number`.  

JavaScript cung cấp những phương tiện khác nhau để có thể coercing giữa các *types* khác nhau. Ví dụ:

```js
var a = "42";
var b = Number( a );

console.log( a );	// "42"
console.log( b );	// 42
```

Sử dụng `Number(..)` (một built-in function) như trên là một cách coercion trực quan để chuyển đổi những type khác nhau thành `number`. Điều này khá rõ ràng để nhìn ra.

Nhưng một chủ đề gây tranh cãi là điều gì sẽ xảy ra nếu bạn cố gắng so sánh 2 giá trị không cùng kiểu với nhau, lúc đó nó sẽ dẫn đến việc coercion ngầm định.

Khi bạn so sánh chuỗi `"99.99"` với con số `99.99`, đa phần mọi người sẽ đồng ý là nó tương đương nhau.
Nhưng bản thân chúng không hoàn toàn giống nhau, nó chỉ là hai thứ giống nhau về giá trị nhưng cách hiển thị hoàn toàn khác nhau, hay nói cách khác là hai kiểu khác nhau. Bạn có thể gọi chúng là "loosely equal", phải không?

Để giúp bạn trong những tình huống rất hay xảy ra này, JavaScript đôi khi sẽ nhảy vào và ép buộc sự coercion ngầm định để cho 2 giá trị bằng nhau.

Vì vậy nếu bạn sử dụng `==` (loose equal) để so sánh `"99.99" == 99.99`, JavaScript sẽ chuyển đổi vế trái `"99.99"` thành `number` tương ứng là `99.99`. Do đó việc so sánh sẽ trở thành `99.99 == 99.99`, và đó tất nhiên là một phép so sánh trả lại kết quả `true`.

Tuy thiết kế để hữu dụng hơn cho bạn, coercion ngầm định có thể gây ra nhầm lẫn nếu bạn không bỏ thời gian tìm hiểu các quy tắc chi phối hành vi của nó. Đa phần các JS developers không bao giờ bỏ công tìm hiểu nó cho nên có một cảm giác chung cho rằng coercion ngầm định là một điều khó hiểu và gây hại chương trình với những lỗi không ngờ tới, và do đó cần phải tránh. Đôi khi người ta còn gọi nó là một lỗi thiết kế của ngôn ngữ.

Tuy nhiên, coercion ngầm định là một cơ chế có thể học được, và hơn thế nữa nó cần được học cẩn thận nếu bạn thực sự muốn học JavaScript một cách nghiêm túc. Không phải chỉ vì bạn sẽ tránh được sự khó hiểu khi gặp nó mà ngoài ra bạn có thể làm cho chương trình của bạn chạy tốt hơn. Và lúc đó bạn sẽ thấy nỗ lực của bạn được đền đáp xứng đáng.

**Note:** Để biết thêm thông tin về coercion, xin tìm hiểu thêm ở Chương 2 của cuốn sách này hoặc Chương 4 của cuốn *Types & Grammar*.

## Code Comments

Các nhân viên của cửa hàng điện thoại có thể ghi lại một số ghi chú về các tính năng của một chiếc điện thoại mới được phát hành hoặc các kế hoạch mới của công ty đưa ra. Các ghi chú này chỉ dành riêng cho nhân viên công ty -- nó không dành cho khác hàng. Tuy nhiên, những ghi chú này giúp cho nhân viên có thể làm việc tốt hơn bằng cách hệ thống hoá lại những câu hỏi "hows and whys" về những điều họ nên nói với khách hàng.

Một trong những bài học quan trọng nhất mà bạn cần học về viết code đó là nó không chỉ viết ra cho máy tính. Một chút gì đó nên hiểu rẳng nó còn dành cho các developers nữa.

Máy tính của bạn chỉ quan tâm đến mã máy, đó là một loạt các dãy số 0 và 1, đến từ việc biên dịch code. Có một số lượng gần như vô hạn các chương trình mà bạn có thể viết ra từ những dãy số 0 và 1. Bạn có quyền lựa chọn cách viết chương trình -- không chỉ cho bản thân bạn, mà còn cho những người trong teams và thậm chí cho chính bản thân bạn trong tương lai nữa.

Bạn nên cố gắng không chỉ viết ra một chương trình chạy được, mà còn là một chương trình có ý nghĩa khi cần kiểm tra lại nó. Bạn có thể bắt đầu nỗ lực dài hơi đó bằng việc lựa chọn những cái tên tốt cho các biến (Xem thêm phần "Variables") và các hàm của bạn (Xem thêm phần "Functions").

Nhưng một phần không kém quan trọng là code comments. Nó đơn giản chỉ là những đoạn text bạn đặt vào trong chương trình để giải thích cho người đọc. Khi chạy, các thông dịch/biên dịch sẽ luôn bỏ qua những comments này.

Có rất nhiều ý kiến về những điều gì làm nên những comments tốt, chúng ta thực sự rất khó để xác định các quy tắc phổ quát. Nhưng có một số quan sát và hướng dẫn khá hữu ích như sau:

* Code không có comments thì không phải là tối ưu.
* Quá nhiều comments (ví dụ trên cùng một dòng) là biểu hiện của đoạn code kém.
* Comments nên dành để giải thích câu hỏi *Tại sao* chứ không phải là câu hỏi *Cái gì* (should explain *why*, not *what*). Có thể tuỳ chọn giải thích câu hỏi *làm thế nào* (question *how*) nếu như nó thực sự gây khó hiểu.

Trong JavaScript, có hai loại comments: comment đơn dòng (single-line comment) và comment nhiều dòng (multiline comment).

Xem xét:

```js
// This is a single-line comment

/* But this is
       a multiline
             comment.
                      */
```
Ký tự `//` trong comment đơn dòng được sử dụng khi bạn đặt dòng comment ngay trên một statement, hoặc ngay cuối dòng. Tất cả mọi thứ ngay sau ký tự `//` đến tận cuối dòng thì được xem như là comment (và tất nhiên nó sẽ bị bỏ qua khi biên dịch). Không có hạn chế với những gì có thể xuất hiện bên trong một comment đơn dòng.

Xem xét:

```js
var a = 42;		// 42 is the meaning of life
```

Ký tự `/* .. */` trong comment đa dòng được dùng khi bạn muốn đặt nhiều dòng comments để giải thích cho đoạn code của bạn.

Sau đây là cách dùng phổ biến của comment đa dòng:

```js
/* The following value is used because
   it has been shown that it answers
   every question in the universe. */
var a = 42;
```

Comment đa dòng có thể xuất hiện bất kỳ đâu trong câu lệnh, ngay cả khi ở chính giữa câu, vì nó có ký tự `*/` để chỉ ra sự kết thúc của nó. Ví dụ:

```js
var a = /* arbitrary value */ 42;

console.log( a );	// 42
```

Điều duy nhất không thể xuất hiện ở trong một comment đa dòng là ký tự `*/`, bởi nó sẽ làm cho trình phiên dịch hiểu rằng đó là điểm kết thúc của comment.

Bạn chắc chắn sẽ muốn bắt đầu quá trình học lập trình bằng cách học thói quen viết các comments. Xuyên suốt những phần còn lại của chương này, bạn sẽ thấy tôi sử dụng comment để giải thích cho mọi thứ, vì vậy tôi muốn bạn cũng làm tương tự như vậy trong các bài thực hành của bạn. Tin tôi đi, tất cả những người đọc code của bạn sẽ cảm ơn bạn vì điều đó.

## Biến (Variables)

Những chương trình hiệu quả cần phải theo dõi các giá trị đã thay đổi như thế nào trong toàn bộ chương trình, khi đã trải qua các hoạt động khác nhau được bạn gọi ra trong chương trình của bạn.

Cách dễ nhất để thực hiện điều đó trong chương trình của bạn là gán giá trị đó vào một cái hộp tượng trưng nào đó, được gọi là các biến *variable* -- nó được gọi thế vì giá trị bên trong chiếc hộp này có thể thay đổi *vary* theo thời gian nếu muốn.

Trong một số ngôn ngữ lập trình, bạn khai báo một variable và cho nó nắm giữ một kiểu cụ thể của một giá trị, ví dụ như `number` hoặc `string`. Kiểu tĩnh *Static typing*, hay còn gọi là kiễu cưỡng chế *type enforcement*, thường được xem là một lợi ích cho chương trình vì nó ngăn không cho sự chuyển đổi giá trị xảy ra ngoài ý muốn.

Những ngôn ngữ lập trình khác lại nhấn mạnh vào các kiểu cho giá trị thay vì các biến, *Weak typing*, hay còn được gọi là Kiểu động *dynamic typing*, cho phép một biến có thể giữ tất cả các kiểu của giá trị bất cứ lúc nào nó muốn. Nó thường được nhìn nhận như là một cách làm cho chương trình linh hoạt hơn bằng cách cho phép một biến duy nhất đại diện cho một giá trị nào đó và không cần quan tâm đến kiểu của giá trị đó mà nó có thể được gán vào ở bất kỳ thời điểm nào trong dòng logic của chương trình.

JavaScript có cách tiếp cận thứ hai, Kiểu động *dynamic typing*, nghĩa là variables có thể giữ giá trị của bất kỳ kiểu nào mà không cần cưỡng chế kiểu vào nó.

Như đã đề cập trước đó, chúng ta khai báo variable sử dụng từ khoá `var` -- để ý là chúng ta không cần khai báo các thông tin về kiểu trong đó. Xem xét ví dụ đơn giản sau:

```js
var amount = 99.99;

amount = amount * 2;

console.log( amount );		// 199.98

// convert `amount` to a string, and
// add "$" on the beginning
amount = "$" + String( amount );

console.log( amount );		// "$199.98"
```

Biến `amount` bắt đầu bằng việc nắm giữ giá trị của number `99.99`, và sau đó nắm giữ giá trị number của kết quả `amount * 2` là `199.98`.

Câu lệnh `console.log(..)` số một phải thực hiện coerce ngầm định đó là chuyển đổi `number` thành `string` để in ra.

Sau đó câu lệnh `amount = "$" + String(amount)` sẽ trực tiếp coerce giá trị `199.98` thành một chuỗi và thêm vào ký tự `$` vào phía trước. Ở thời điểm này, biến `amount` nắm giữ chuỗi `"$199.98"`, do đó câu lệnh `console.log(...)` số hai khi kết quả ra, không cần thiết phải làm bất kỳ một coercion nào nữa.   

JavaScript developers sẽ nhận thấy sự linh hoạt của việc sử dụng biến `amount` cho các giá trị `99.99`, `199.98` và cho chuỗi `"$199.98"`. Những người đam mê kiểu tĩnh *Static-typing* sẽ cần phải có thêm một biến độc lập kiểu như là `amountStr` để nắm giữ giá trị cuối cùng của chuỗi `"$199.98"` bởi vì kiểu của nó khác với kiểu trước.

Cách nào đi nữa, bạn cũng sẽ nhận thấy rằng biến `amount` nắm giữ một giá trị có sự thay đổi trong quá trình hoạt động của chương trình, nó minh hoạ cho mục đích chính của biến đó là: quản lý các *states* của chương trình.

Hay nói cách khác, *states* theo dõi những sự thay đổi của giá trị khi chương trình hoạt động.

Một cách sử dụng phổ biến khác của biến là sự thiết lập giá trị trung tâm. Nó thường được gọi là hằng số *constants*, đó là khi bạn khai báo một biến với một giá trị nào đó và không có ý định thay đổi giá trị của nó trong toàn bộ chương trình.

Bạn khai báo các hằng số *constants* thông thường ở phía trên cùng của chương trình, việc này cũng thuận tiện cho bạn nếu bạn muốn gán cho nó một giá trị khác. Theo quy ước, trong JavaScript các hằng số thường được viết hoa và có dấu gạch chân `_` ở giữa các từ.

Sau đây là một ví dụ hơi ngu ngơ:

```js
var TAX_RATE = 0.08;	// 8% sales tax

var amount = 99.99;

amount = amount * 2;

amount = amount + (amount * TAX_RATE);

console.log( amount );				// 215.9784
console.log( amount.toFixed( 2 ) );	// "215.98"
```

**Note:** Tương tự như trong `console.log(..)` hàm `log(..)` được gọi đến như là một object property từ `console`, thì hàm `toFixed(..)` ở đây cũng là một object property của `number`. Trong JavaScript, `number` không được gán cho đơn vị tiền tệ -- engine của Javascript không biết được ý định của bạn là gì và cũng không có loại định dạng cho tiền tệ. Cho nên hàm `toFixed(..)` giúp chúng ta xác định có bao nhiêu chữ số ở phần thập phân, và nó cũng tạo ra kiểu chuỗi `string` nếu cần thiết.  

Biến `TAX_RATE` được xem là hằng số *constant* theo quy ước -- không có điều kiện áp đặt nào trong chương trình ngăn nó không được thay đổi. Nhưng nếu như chính quyền thành phố tăng thuế bán hàng lên thành 9%, chúng ta cũng có thể dễ dàng thay đổi chương trình của chúng ta bằng cách đặt lại giá trị của `TAX_RATE` thành `0.09` ở ngay đầu chương trình mà không phải tìm kiếm nhiều lần xuất hiện của giá trị `0.08` rải rác trong suốt chương trình và cập nhật tất cả chúng.

Phiên bản mới nhất của JavaScript ở thời điểm viết (thường được gọi là "ES6") có kèm thêm một cách mới để khai báo các hàng số bằng cách sử dụng từ khoá `const` thay cho từ khoá `var`:

```js
// as of ES6:
const TAX_RATE = 0.08;

var amount = 99.99;

// ..
```

Hằng số có giá trị sử dụng giống như là các biến với giá trị không đổi, ngoại trừ việc hằng số ngăn không cho nó vô tình bị thay đổi ở một đoạn code nào đó trong chương trình, sau khi đã được gán giá trị ban đầu. Nếu bạn cố thay gán một giá trị khác cho `TAX_RATE` sau khi bạn đã khai báo nó, chương trình của bạn sẽ từ chối các thay đổi đó (và trong những chế độ cài đặt nghiêm ngặt, nó sẽ phát sinh lỗi -- xem thêm phần "Strict Mode" trong Chương 2).

Bằng cách này, việc "bảo vệ" sự vô tình thay đổi giá trị của hằng số sẽ tương tự như việc thực thi của kiểu tĩnh (Static-typing), đó cũng là một lý do hấp dẫn của kiểu tĩnh trong những ngôn ngữ khác!

**Note:** Để biết thêm thông tin về cách sử dụng các giá trị khác nhau của biến trong chương trình, bạn có thể xem thêm phần *Type & Grammar* trong series sách này.

## Blocks

Nhân viên cửa hàng điện thoại phải đi qua rất nhiều bước để hoàn thành việc thanh toán khi bạn mua điện thoại của họ.

Tương tự như vậy, trong lập trình chúng ta thường cần một nhóm các series chứa các câu lệnh đi cùng với nhau, mà chúng ta thường gọi là *block*. Trong JavaScript, một block được xác định bằng cách gói một hoặc nhiều câu lệnh bên trong một cặp ngoặc đơn `{ .. }`. Xem xét ví dụ sau:

```js
var amount = 99.99;

// a general block
{
	amount = amount * 2;
	console.log( amount );	// 199.98
}
```
Kiẻu cặp ngoặc đơn `{ .. }` đứng một mình như thế này hoàn toàn hợp lệ, nhưng nó không thường được sử dụng trong JavaScript. Thông thường, block được sử dụng trong các câu lệnh điều khiểu, ví dụ như `if` (Xem thêm phần "Conditionals") hoặc vòng lặp (Xem thêm phần "Loops"). Ví dụ như:

```js
var amount = 99.99;

// is amount big enough?
if (amount > 10) {			// <-- block attached to `if`
	amount = amount * 2;
	console.log( amount );	// 199.98
}
```

Chúng ta sẽ giải thích câu lệnh `if` trong những phần tới, nhưng bạn có thể thấy, cặp ngoặc đơn `{ .. }` chứa 2 câu lệnh trong đó, được gắn với phần điều kiện `if (amount > 10)`; Các câu lệnh bên trong khối đó chỉ được xử lý nếu điều kiện đó xảy ra.

**Note:** Không giống như những câu lệnh khác, kiểu như `console.log(amount);`, một block không cần phải có dấm chấm phẩy cuối câu.

## Conditionals

"Do you want to add on the extra screen protectors to your purchase, for $9.99?" The helpful phone store employee has asked you to make a decision. And you may need to first consult the current *state* of your wallet or bank account to answer that question. But obviously, this is just a simple "yes or no" question.

There are quite a few ways we can express *conditionals* (aka decisions) in our programs.

The most common one is the `if` statement. Essentially, you're saying, "*If* this condition is true, do the following...". For example:

```js
var bank_balance = 302.13;
var amount = 99.99;

if (amount < bank_balance) {
	console.log( "I want to buy this phone!" );
}
```

The `if` statement requires an expression in between the parentheses `( )` that can be treated as either `true` or `false`. In this program, we provided the expression `amount < bank_balance`, which indeed will either evaluate to `true` or `false` depending on the amount in the `bank_balance` variable.

You can even provide an alternative if the condition isn't true, called an `else` clause. Consider:

```js
const ACCESSORY_PRICE = 9.99;

var bank_balance = 302.13;
var amount = 99.99;

amount = amount * 2;

// can we afford the extra purchase?
if ( amount < bank_balance ) {
	console.log( "I'll take the accessory!" );
	amount = amount + ACCESSORY_PRICE;
}
// otherwise:
else {
	console.log( "No, thanks." );
}
```

Here, if `amount < bank_balance` is `true`, we'll print out `"I'll take the accessory!"` and add the `9.99` to our `amount` variable. Otherwise, the `else` clause says we'll just politely respond with `"No, thanks."` and leave `amount` unchanged.

As we discussed in "Values & Types" earlier, values that aren't already of an expected type are often coerced to that type. The `if` statement expects a `boolean`, but if you pass it something that's not already `boolean`, coercion will occur.

JavaScript defines a list of specific values that are considered "falsy" because when coerced to a `boolean`, they become `false` -- these include values like `0` and `""`. Any other value not on the "falsy" list is automatically "truthy" -- when coerced to a `boolean` they become `true`. Truthy values include things like `99.99` and `"free"`. See "Truthy & Falsy" in Chapter 2 for more information.

*Conditionals* exist in other forms besides the `if`. For example, the `switch` statement can be used as a shorthand for a series of `if..else` statements (see Chapter 2). Loops (see "Loops") use a *conditional* to determine if the loop should keep going or stop.

**Note:** For deeper information about the coercions that can occur implicitly in the test expressions of *conditionals*, see Chapter 4 of the *Types & Grammar* title of this series.

## Loops

During busy times, there's a waiting list for customers who need to speak to the phone store employee. While there's still people on that list, she just needs to keep serving the next customer.

Repeating a set of actions until a certain condition fails -- in other words, repeating only while the condition holds -- is the job of programming loops; loops can take different forms, but they all satisfy this basic behavior.

A loop includes the test condition as well as a block (typically as `{ .. }`). Each time the loop block executes, that's called an *iteration*.

For example, the `while` loop and the `do..while` loop forms illustrate the concept of repeating a block of statements until a condition no longer evaluates to `true`:

```js
while (numOfCustomers > 0) {
	console.log( "How may I help you?" );

	// help the customer...

	numOfCustomers = numOfCustomers - 1;
}

// versus:

do {
	console.log( "How may I help you?" );

	// help the customer...

	numOfCustomers = numOfCustomers - 1;
} while (numOfCustomers > 0);
```

The only practical difference between these loops is whether the conditional is tested before the first iteration (`while`) or after the first iteration (`do..while`).

In either form, if the conditional tests as `false`, the next iteration will not run. That means if the condition is initially `false`, a `while` loop will never run, but a `do..while` loop will run just the first time.

Sometimes you are looping for the intended purpose of counting a certain set of numbers, like from `0` to `9` (ten numbers). You can do that by setting a loop iteration variable like `i` at value `0` and incrementing it by `1` each iteration.

**Warning:** For a variety of historical reasons, programming languages almost always count things in a zero-based fashion, meaning starting with `0` instead of `1`. If you're not familiar with that mode of thinking, it can be quite confusing at first. Take some time to practice counting starting with `0` to become more comfortable with it!

The conditional is tested on each iteration, much as if there is an implied `if` statement inside the loop.

We can use JavaScript's `break` statement to stop a loop. Also, we can observe that it's awfully easy to create a loop that would otherwise run forever without a `break`ing mechanism.

Let's illustrate:

```js
var i = 0;

// a `while..true` loop would run forever, right?
while (true) {
	// stop the loop?
	if ((i <= 9) === false) {
		break;
	}

	console.log( i );
	i = i + 1;
}
// 0 1 2 3 4 5 6 7 8 9
```

**Warning:** This is not necessarily a practical form you'd want to use for your loops. It's presented here for illustration purposes only.

While a `while` (or `do..while`) can accomplish the task manually, there's another syntactic form called a `for` loop for just that purpose:

```js
for (var i = 0; i <= 9; i = i + 1) {
	console.log( i );
}
// 0 1 2 3 4 5 6 7 8 9
```

As you can see, in both cases the conditional `i <= 9` is `true` for the first 10 iterations (`i` of values `0` through `9`) of either loop form, but becomes `false` once `i` is value `10`.

The `for` loop has three clauses: the initialization clause (`var i=0`), the conditional test clause (`i <= 9`), and the update clause (`i = i + 1`). So if you're going to do counting with your loop iterations, `for` is a more compact and often easier form to understand and write.

There are other specialized loop forms that are intended to iterate over specific values, such as the properties of an object (see Chapter 2) where the implied conditional test is just whether all the properties have been processed. The "loop until a condition fails" concept holds no matter what the form of the loop.

## Functions

The phone store employee probably doesn't carry around a calculator to figure out the taxes and final purchase amount. That's a task she needs to define once and reuse over and over again. Odds are, the company has a checkout register (computer, tablet, etc.) with those "functions" built in.

Similarly, your program will almost certainly want to break up the code's tasks into reusable pieces, instead of repeatedly repeating yourself repetitiously (pun intended!). The way to do this is to define a `function`.

A function is generally a named section of code that can be "called" by name, and the code inside it will be run each time. Consider:

```js
function printAmount() {
	console.log( amount.toFixed( 2 ) );
}

var amount = 99.99;

printAmount(); // "99.99"

amount = amount * 2;

printAmount(); // "199.98"
```

Functions can optionally take arguments (aka parameters) -- values you pass in. And they can also optionally return a value back.

```js
function printAmount(amt) {
	console.log( amt.toFixed( 2 ) );
}

function formatAmount() {
	return "$" + amount.toFixed( 2 );
}

var amount = 99.99;

printAmount( amount * 2 );		// "199.98"

amount = formatAmount();
console.log( amount );			// "$99.99"
```

The function `printAmount(..)` takes a parameter that we call `amt`. The function `formatAmount()` returns a value. Of course, you can also combine those two techniques in the same function.

Functions are often used for code that you plan to call multiple times, but they can also be useful just to organize related bits of code into named collections, even if you only plan to call them once.

Consider:

```js
const TAX_RATE = 0.08;

function calculateFinalPurchaseAmount(amt) {
	// calculate the new amount with the tax
	amt = amt + (amt * TAX_RATE);

	// return the new amount
	return amt;
}

var amount = 99.99;

amount = calculateFinalPurchaseAmount( amount );

console.log( amount.toFixed( 2 ) );		// "107.99"
```

Although `calculateFinalPurchaseAmount(..)` is only called once, organizing its behavior into a separate named function makes the code that uses its logic (the `amount = calculateFinal...` statement) cleaner. If the function had more statements in it, the benefits would be even more pronounced.

### Scope

If you ask the phone store employee for a phone model that her store doesn't carry, she will not be able to sell you the phone you want. She only has access to the phones in her store's inventory. You'll have to try another store to see if you can find the phone you're looking for.

Programming has a term for this concept: *scope* (technically called *lexical scope*). In JavaScript, each function gets its own scope. Scope is basically a collection of variables as well as the rules for how those variables are accessed by name. Only code inside that function can access that function's *scoped* variables.

A variable name has to be unique within the same scope -- there can't be two different `a` variables sitting right next to each other. But the same variable name `a` could appear in different scopes.

```js
function one() {
	// this `a` only belongs to the `one()` function
	var a = 1;
	console.log( a );
}

function two() {
	// this `a` only belongs to the `two()` function
	var a = 2;
	console.log( a );
}

one();		// 1
two();		// 2
```

Also, a scope can be nested inside another scope, just like if a clown at a birthday party blows up one balloon inside another balloon. If one scope is nested inside another, code inside the innermost scope can access variables from either scope.

Consider:

```js
function outer() {
	var a = 1;

	function inner() {
		var b = 2;

		// we can access both `a` and `b` here
		console.log( a + b );	// 3
	}

	inner();

	// we can only access `a` here
	console.log( a );			// 1
}

outer();
```

Lexical scope rules say that code in one scope can access variables of either that scope or any scope outside of it.

So, code inside the `inner()` function has access to both variables `a` and `b`, but code in `outer()` has access only to `a` -- it cannot access `b` because that variable is only inside `inner()`.

Recall this code snippet from earlier:

```js
const TAX_RATE = 0.08;

function calculateFinalPurchaseAmount(amt) {
	// calculate the new amount with the tax
	amt = amt + (amt * TAX_RATE);

	// return the new amount
	return amt;
}
```

The `TAX_RATE` constant (variable) is accessible from inside the `calculateFinalPurchaseAmount(..)` function, even though we didn't pass it in, because of lexical scope.

**Note:** For more information about lexical scope, see the first three chapters of the *Scope & Closures* title of this series.

## Practice

There is absolutely no substitute for practice in learning programming. No amount of articulate writing on my part is alone going to make you a programmer.

With that in mind, let's try practicing some of the concepts we learned here in this chapter. I'll give the "requirements," and you try it first. Then consult the code listing below to see how I approached it.

* Write a program to calculate the total price of your phone purchase. You will keep purchasing phones (hint: loop!) until you run out of money in your bank account. You'll also buy accessories for each phone as long as your purchase amount is below your mental spending threshold.
* After you've calculated your purchase amount, add in the tax, then print out the calculated purchase amount, properly formatted.
* Finally, check the amount against your bank account balance to see if you can afford it or not.
* You should set up some constants for the "tax rate," "phone price," "accessory price," and "spending threshold," as well as a variable for your "bank account balance.""
* You should define functions for calculating the tax and for formatting the price with a "$" and rounding to two decimal places.
* **Bonus Challenge:** Try to incorporate input into this program, perhaps with the `prompt(..)` covered in "Input" earlier. You may prompt the user for their bank account balance, for example. Have fun and be creative!

OK, go ahead. Try it. Don't peek at my code listing until you've given it a shot yourself!

**Note:** Because this is a JavaScript book, I'm obviously going to solve the practice exercise in JavaScript. But you can do it in another language for now if you feel more comfortable.

Here's my JavaScript solution for this exercise:

```js
const SPENDING_THRESHOLD = 200;
const TAX_RATE = 0.08;
const PHONE_PRICE = 99.99;
const ACCESSORY_PRICE = 9.99;

var bank_balance = 303.91;
var amount = 0;

function calculateTax(amount) {
	return amount * TAX_RATE;
}

function formatAmount(amount) {
	return "$" + amount.toFixed( 2 );
}

// keep buying phones while you still have money
while (amount < bank_balance) {
	// buy a new phone!
	amount = amount + PHONE_PRICE;

	// can we afford the accessory?
	if (amount < SPENDING_THRESHOLD) {
		amount = amount + ACCESSORY_PRICE;
	}
}

// don't forget to pay the government, too
amount = amount + calculateTax( amount );

console.log(
	"Your purchase: " + formatAmount( amount )
);
// Your purchase: $334.76

// can you actually afford this purchase?
if (amount > bank_balance) {
	console.log(
		"You can't afford this purchase. :("
	);
}
// You can't afford this purchase. :(
```

**Note:** The simplest way to run this JavaScript program is to type it into the developer console of your nearest browser.

How did you do? It wouldn't hurt to try it again now that you've seen my code. And play around with changing some of the constants to see how the program runs with different values.

## Review

Learning programming doesn't have to be a complex and overwhelming process. There are just a few basic concepts you need to wrap your head around.

These act like building blocks. To build a tall tower, you start first by putting block on top of block on top of block. The same goes with programming. Here are some of the essential programming building blocks:

* You need *operators* to perform actions on values.
* You need values and *types* to perform different kinds of actions like math on `number`s or output with `string`s.
* You need *variables* to store data (aka *state*) during your program's execution.
* You need *conditionals* like `if` statements to make decisions.
* You need *loops* to repeat tasks until a condition stops being true.
* You need *functions* to organize your code into logical and reusable chunks.

Code comments are one effective way to write more readable code, which makes your program easier to understand, maintain, and fix later if there are problems.

Finally, don't neglect the power of practice. The best way to learn how to write code is to write code.

I'm excited you're well on your way to learning how to code, now! Keep it up. Don't forget to check out other beginner programming resources (books, blogs, online training, etc.). This chapter and this book are a great start, but they're just a brief introduction.

The next chapter will review many of the concepts from this chapter, but from a more JavaScript-specific perspective, which will highlight most of the major topics that are addressed in deeper detail throughout the rest of the series.
