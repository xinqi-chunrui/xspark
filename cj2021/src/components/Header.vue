<template>
	<div class="wrapper">
		<div class="page_top">
			<div class="main">
				<div class="m-logo">
					<a href="https://changshu.xinghuo100.com/"></a>
				</div>
				<div class="m-logo" style="background: url(../image/hd_xxl_03.png) no-repeat left top;margin-right: 0;margin-left: 15px;"></div>
				<div class="top_left">
					<!--城市选择-->
					<div class="m-selectcity">
						<div class="m-city">
							<i></i>
							<span id="inseachcity">常熟</span>
						</div>
						<div style="" class="area_school" id="selectcity_pop"></div>
					</div>
					<span style="margin-left:10px;"></span>
				</div>
				<div class="top_right">
					<div class="hotline">全国免费咨询热线： <strong>400-877-0068</strong></div>
					<div id="moquu_wxin" class="moquu_wxin">
						<a href="javascript:void(0)"><img src="http://xinghuo100.com/Content/Images/icon_wechat.png" /><span class="wechat">星火教育官微</span>
							<div class="moquu_wxinh"><img src="https://www.xinghuo100.com/kf/ewm/gy.jpg" /></div>
						</a>
					</div>
				</div>
			</div>
			<div class="clear"></div>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Header",
	}
</script>

<style lang="scss">
/** 清除内外边距 **/

body,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
p,
blockquote,

/* structural elements 结构元素 */

dl,
dt,
dd,
ul,
ol,
li,

/* list elements 列表元素 */

pre,

/* text formatting elements 文本格式元素 */

form,
fieldset,
legend,
button,
input,
textarea,

/* form elements 表单元素 */

th,
td
/* table elements 表格元素 */

{
	margin: 0;
	padding: 0;
}


/* CSS Document */

table,
em {
	/*font-family:"Microsoft Yahei",Arial,sans-serif;*/
	font-size: 12px;
	text-align: left;
	margin: 0px auto;
	padding: 0px;
}


/** 设置默认字体 **/

body,
button,
input,
select,
textarea
/* for ie */

{
	font: 14px/1.5 "Source Han Sans CN", "微软雅黑", "Lantinghei SC", tahoma, \5b8b\4f53, sans-serif;
}


/*blockquote, body, dd, div, dl, dt, fieldset, form, h1, h2, h3, h4, h5, h6, input, li, ol, p, pre, td, textarea, th, ul {
    margin: 0;
    padding: 0;
}*/

article,
aside,
dialog,
footer,
header,
section,
footer,
nav,
figure,
menu {
	display: block
}

dd {
	display: block;
}

img {
	border: 0;
	vertical-align: top;
	vertical-align: middle;
}

a {
	color: #9a9a9a;
	text-decoration: none;
}

a:hover {
	text-decoration: none;
}

:focus {
	outline: 0;
}

address,
caption,
cite,
code,
dfn,
em,
th,
var {
	font-style: normal;
	font-weight: 400;
}

.cale li,
.cale_p li,
.m-selectcity,
.selIcon,
.selectBox,
.slidebar li,
.table1 th,
.title2 li,
a,
button,
label {
	cursor: pointer;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	font-weight: 400;
	font-size: 100%
}


/* Forms */

form {
	display: inline;
}

fieldset {
	border: 0;
}

legend {
	display: none;
}


/* Table */

table {
	border: 0;
	/*border-collapse:collapse;*/
	border-spacing: 0;
	empty-cells: show;
	font-size: 100%;
}

caption,
th,
td {
	/*vertical-align:top;*/
	text-align: left;
	font-weight: normal;
}


/* Content */

p {
	margin: 0;
}

strong {
	font-weight: bold;
}

address {
	font-style: normal;
	line-height: 1.35;
}

cite {
	font-style: normal;
}

q,
blockquote {
	quotes: none;
}

q:before,
q:after {
	content: '';
}

small,
big {
	font-size: 1em;
}


/*sup           { font-size:1em; vertical-align:top; }*/


/* Lists */

ul,
ol {
	list-style: none;
}

.clear {
	clear: both;
	font-size: 0px;
	height: 0px;
}

.clearfix:after,
.clearfix:before {
	content: "";
	display: table;
}

.clearfix:after {
	content: '';
	display: block;
	clear: both;
}

.clearfix {
	*zoom: 1;
}

.fl {
	float: left;
}

.fr {
	float: right;
}	
/* header */
.wrapper {
	width: 100%;
	margin: 0px;
	padding: 0px;
}

.main {
	width: 1210px;
	margin: 0px auto;
}

.page {
	width: 100%;
	margin: 0px;
	padding: 0px;
}

.page_top {
	width: 100%;
	background: #FFFFFF;
	border-bottom: 1px #F5F5F5 solid;
	height: 98px;
}

.page_bottom {
	width: 100%;
	background: #FFFFFF;
	border-top: 1px #F5F5F5 solid;
	height: 78px;
	line-height: 78px;
	color: #CCCCCC;
	text-align: center;
}

.m-logo {
	width: 133px;
	height: 67px;
	margin-top: 12px;
	margin-right: 15px;
	/*overflow: hidden;*/
	float: left;
	display: inline;
	background: url('http://www.xinghuo100.com/kf/logo/xh.png') no-repeat left top;
}

.m-logo a {
	position: relative;
	display: block;
	width: 133px;
	height: 67px;
	/*overflow: hidden;*/
	text-indent: -9999px;
}

.m-logo a:after {
	content: '';
	position: absolute;
	right: -15px;
	top: 0;
	bottom: 0;
	margin: auto;
	width: 2px;
	height: 43px;
	background: #7359a1;
}

.top_left {
	width: 329px;
	float: left;
	margin-top: 30px;
	/*background: url(../image/tleft_bg.png) no-repeat left top;*/
	font-size: 16px;
	color: #ADADAD;
}

.top_right {
	width: 420px;
	float: right;
	margin-right: 16px;
	margin-top: 31px;
	font-size: 14px;
	text-align: right;
}

.top_right .hotline {
	margin-right: 29px;
	float: left;
}

.top_right .hotline strong {
	color: #AAC135;
	font-size: 18px;
}	
</style>
