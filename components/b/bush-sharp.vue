<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kmdlzrbcv"/><path class="n5tun1b7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bush-sharp" /></template>
<style>
.kmdlzrbcv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 18.5a4.25 4.25 0 0 1-.23-8.49a5.25 5.25 0 1 1 10.46 0A4.25 4.25 0 0 1 17 18.5Zm-4.25 2.75h18.5");
}

.n5tun1b7s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 14.5h.01M12.5 11h.01m3.24 4.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
