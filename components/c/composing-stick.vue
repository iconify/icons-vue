<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ymte612km"/><path class="guywwzmjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:composing-stick" /></template>
<style>
.guywwzmjw {
  d: path("M7.75 9.5H16v5H7.75Zm2.75 0v5m2.75-5v5m5.5 0V9H21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymte612km {
  d: path("M2.5 5.5H5v9h16.5V18h-19Z");
}

</style>
