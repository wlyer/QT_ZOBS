<template>
	<section class="my-contact">
		<h2 ><strong class="title">{{$route.name}}</strong></h2>
		<div class="my-contact-detail">
		</div>
	</section>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		methods: {
		},
		computed: {
	    },
		mounted() {
		},
		components: {
		}
	}

</script>

<style scoped lang="scss">
.my-contact{
	.title{
		padding:0 10px 0 30px;
		border-right: 3px solid #c7161c;
	}
	.my-contact-detail{
		padding-top: 50px;
		width: 60%;
		margin: auto;
	}
}
</style>