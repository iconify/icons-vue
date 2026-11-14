<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cdv9e9b3j"/><path class="i-3hmub1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-bottle-warmer" /></template>
<style>
.cdv9e9b3j {
  d: path("M10 6V4.5a2 2 0 0 1 4 0V6M8 6h8v2.5H8Zm.5 2.5V16a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2V8.5");
}

.i-3hmub1m {
  d: path("M5 11v7a3.5 3.5 0 0 0 3.5 3.5h7A3.5 3.5 0 0 0 19 18v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
