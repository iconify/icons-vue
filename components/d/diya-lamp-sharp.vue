<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjxlqlbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diya-lamp-sharp" /></template>
<style>
.xjxlqlbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.5h17.5a8.75 7 0 0 1-17.5 0ZM12 3.75C13.75 5.5 14.75 7 14.75 8.5a2.75 2.75 0 0 1-5.5 0c0-1.5 1-3 2.75-4.75ZM6.25 16h11.5");
}

</style>
