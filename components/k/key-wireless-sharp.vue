<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xjlwmlrxu"/><path class="jdinfrbxs"/><path class="ow73bhs5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-wireless-sharp" /></template>
<style>
.jdinfrbxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.96 7.25a3 3 0 1 0-3.46 3.46");
}

.ow73bhs5r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 11.75h.01M13.5 16h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xjlwmlrxu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 7.25H19.5V20.5h-12V7.25z");
}

</style>
