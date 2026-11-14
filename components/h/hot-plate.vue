<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzvev9bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-plate" /></template>
<style>
.nzvev9bcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 14.5h12.5a3.25 3.25 0 0 1 3.25 3.25A3.25 3.25 0 0 1 18.25 21H5.75a3.25 3.25 0 0 1-3.25-3.25a3.25 3.25 0 0 1 3.25-3.25M6 17.75h5M7 11.5Q5.5 9.25 7 7.25Q8.5 5 7 3m5 8.5q-1.5-2.25 0-4.25Q13.5 5 12 3m5 8.5q-1.5-2.25 0-4.25Q18.5 5 17 3");
}

</style>
