<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx7bj6pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-outline-sharp" /></template>
<style>
.lpx7bj6pb {
  fill: currentColor;
  d: path("M11.5 19.714v-7.427L5 8.523v7.427zm1 0L19 15.95V8.523l-6.5 3.764zm-.5-8.287l6.425-3.713L12 4L5.575 7.714zm-8 5.121V7.452l8-4.598l8 4.598v9.096l-8 4.598zM12 12");
}

</style>
