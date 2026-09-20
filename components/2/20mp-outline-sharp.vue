<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxf82r-_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:20mp-outline-sharp" /></template>
<style>
.wxf82r-_x {
  fill: currentColor;
  d: path("M6.5 11.5H11V10H8V9h3V5.5H6.5V7h3v1h-3zm6.5 0h4.5v-6H13zm1.5-1.5V7H16v3zM6 18.5h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm7.5 0H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
