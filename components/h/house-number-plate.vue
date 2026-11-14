<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bbbky7bkp"/><path class="gy5poyn3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-number-plate" /></template>
<style>
.bbbky7bkp {
  d: path("M3 9h18v12H3Zm3.5-2.75L12 2.5l5.5 3.75");
}

.gy5poyn3y {
  d: path("M13.5 18.25v-6.5L9.5 16H16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
