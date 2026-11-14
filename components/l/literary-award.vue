<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uatb60qjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:literary-award" /></template>
<style>
.uatb60qjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10v6A5 5 0 0 1 7 9Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5v3.75M5.5 18Q9 16.75 12 18q3-1.25 6.5 0v3.5q-3.5-1.25-6.5 0q-3-1.25-6.5 0Z");
}

</style>
