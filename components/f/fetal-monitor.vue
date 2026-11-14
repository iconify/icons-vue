<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znu1b3eig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fetal-monitor" /></template>
<style>
.znu1b3eig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.299 18.033A4.6 4.6 0 0 1 10.5 18l-.25 3.5H5V17c-.75-1.5-1.25-4-1-6c.25-1.5.75-2.5 1.5-2.5h3c1 0 1.5.5 1.75 1.5l.25 1c1.538.461 2.697 1.301 3.304 2.345M5.25 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1 9.75h8.5m1.5 3.5q1.875-5.625 3.75 0t3.75 0");
}

</style>
