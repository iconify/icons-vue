<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kih52ac1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-sensor" /></template>
<style>
.kih52ac1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 8l1.5-3.25Q7 4 8 4h8q1 0 1.5.75L19 8M3 8h18v5H3Zm9 2.5h.01M8.5 15.75q3.5 2 7 0M6 19q6 3.5 12 0");
}

</style>
