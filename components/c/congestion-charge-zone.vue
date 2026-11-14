<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yh3o8-b_d"/><path class="zla5xc92p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:congestion-charge-zone" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yh3o8-b_d {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Z");
}

.zla5xc92p {
  d: path("M14.5 9.5c0-1.25-1.25-1.75-2.5-1.75c-1.5 0-2.5.75-2.5 2c0 2.75 5 1.75 5 4.5c0 1.25-1 2-2.5 2c-1.25 0-2.5-.5-2.5-1.75m2.5-8v11");
}

</style>
