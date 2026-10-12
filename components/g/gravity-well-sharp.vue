<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wkjif9iyf"/><path class="wcpvigl8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gravity-well-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wcpvigl8r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10h.01");
}

.wkjif9iyf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5c5.5 0 7.75 4.5 7.75 15m10.75-15c-5.5 0-7.75 4.5-7.75 15");
}

</style>
