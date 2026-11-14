<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doo62ub8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:erhu" /></template>
<style>
.doo62ub8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5V15m-3 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6 4.5h2.5M6 7.5h2.5m5 13.5q6-8 3.5-17.5");
}

</style>
