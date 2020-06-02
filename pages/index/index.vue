<template>
	<view>
		<view class="status_bar">
			  <!-- 这里是状态栏 -->
		</view>
		<view class="home_header">
			<view class="header_bar">
				<view>京东</view>
				<view>
					<icon type="download" size="16"/>
					<icon type="search" size="16"/>
				</view>
			</view>
			<view class="header_search">
				<view class="search_box">
					<icon type="search" ></icon>
					<input type="text" value="" />
					<icon type="cancel" ></icon>
				</view>
			</view>
			<view class="header_empty">
				<view class="empty_box">
					
				</view>
				<view class="empty_swiper">
					1212
				</view>
			</view>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
.status_bar {
	height: var(--status-bar-height);
	width: 100%;
	background-color: #C92519;
}
.home_header{
	background-color: #C92519;
}
.header_bar{
	display: flex;
	justify-content: space-between;
}
.header_search{
	padding: 10px 0;
}
.search_box{
	height: 30px;
	width: 300px;
	padding: 0 10px;
	background-color: #FFFFFF;
	border-radius: 15px;
	margin: 0 auto;
	display: flex;
	align-items: center;
}
.header_empty{
	background-color: #FFFFFF;
	position: relative;
}
.empty_box{
	background-color: #C92519;
	height: 100px;
}
.empty_swiper{
	height: 200px;
	background-color: #eeeeee;
	margin:  0 20px;
	width: 100%;
	position: absolute;
	top: 0;
}
</style>
