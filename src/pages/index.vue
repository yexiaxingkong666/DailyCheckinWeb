<template>
	<div>
		<div class="grid grid-cols-3">
			<a href="https://vitejs.dev" target="_blank">
				<img :src="safeResolve('/vite.svg')" class="logo" alt="Vite logo" />
			</a>
			<a href="https://vuejs.org/" target="_blank">
				<img :src="safeResolve('/vue.svg')" class="logo vue" alt="Vue logo" />
			</a>
			<a href="https://github.com/yexiaxingkong666" target="_blank">
				<img :src="safeResolve('/yexiaxingkong666.svg')" class="logo YeTech" alt="YeTech logo" />
			</a>
		</div>
		<HelloWorld msg="Daily Check-in" />
	</div>
</template>

<style>
.logo {
	width: 10em;
	height: 10em;
	padding: 1.5rem;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 1em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 1em #42b883aa);
}
.logo.YeTech:hover {
	filter: drop-shadow(0 0 1em #66CCFFaa);
}
</style>
