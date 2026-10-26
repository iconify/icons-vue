<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e789ouica"/><path class="kc33abbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-sharp-two-tone" /></template>
<style>
.e789ouica {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.6924 9L21 9C21.5523 9 22 9.4477 22 10L22 20C22 20.5523 21.5523 21 21 21L17.5 21C17.0411 21 16.6411 20.6877 16.5299 20.2425L16.2192 19L7.7808 19L7.4701 20.2425C7.3589 20.6877 6.9589 21 6.5 21L3 21C2.4477 21 2 20.5523 2 20L2 10C2 9.4477 2.4477 9 3 9L4.3076 9L4.3941 8.7122C4.405 8.6759 4.418 8.6401 4.433 8.6052L6.5812 3.6052C6.739 3.238 7.1003 3 7.5 3L16.5 3C16.8997 3 17.261 3.238 17.4188 3.6053L19.567 8.6053C19.582 8.6401 19.595 8.6758 19.6059 8.7122L19.6924 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kc33abbzy {
  d: path("M3 10L21 10L21 20L17.5 20L17 18L7 18L6.5 20L3 20ZM5.0513 10L5.35177 9L7.5 4L16.5 4L18.6482 9L18.9487 10M5.35177 9L2.5 9M18.6482 9L21.5 9M8 12.5L8 15.5M16 12.5L16 15.5");
}

</style>
