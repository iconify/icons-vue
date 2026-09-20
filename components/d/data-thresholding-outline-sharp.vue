<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjrr8b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-thresholding-outline-sharp" /></template>
<style>
.gtjrr8b9h {
  fill: currentColor;
  d: path("M3 21V3h18v18zm14.275-2H19v-1.725zM5.85 19h1.825l3-3H12.8l-3 3h1.6l3-3h2.125l-3 3h1.625l3-3H19V5H5v12.725L6.725 16H8.85zm1.8-5l-1.4-1.4l4.425-4.425l2 2L16.35 6.5l1.4 1.4l-5.075 5.1l-2-2zM5 19V5z");
}

</style>
