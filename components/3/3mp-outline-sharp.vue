<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qk72e4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3mp-outline-sharp" /></template>
<style>
.r_qk72e4k {
  fill: currentColor;
  d: path("M10 11.5h4.5v-6H10V7h3v1h-2v1h2v1h-3zm-4 7h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm7.5 0H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
