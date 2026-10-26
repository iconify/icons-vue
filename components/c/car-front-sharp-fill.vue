<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="l1p7cccrt"/><path class="zggqekb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l1p7cccrt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.6924 9L21 9C21.5523 9 22 9.4477 22 10L22 20C22 20.5523 21.5523 21 21 21L17.5 21C17.0411 21 16.6411 20.6877 16.5299 20.2425L16.2192 19L7.7808 19L7.4701 20.2425C7.3589 20.6877 6.9589 21 6.5 21L3 21C2.4477 21 2 20.5523 2 20L2 10C2 9.4477 2.4477 9 3 9L4.3076 9L4.3941 8.7122C4.405 8.6759 4.418 8.6401 4.433 8.6052L6.5812 3.6052C6.739 3.238 7.1003 3 7.5 3L16.5 3C16.8997 3 17.261 3.238 17.4188 3.6053L19.567 8.6053C19.582 8.6401 19.595 8.6758 19.6059 8.7122L19.6924 9ZM6.4402 9L17.5598 9L15.8413 5L8.1587 5L6.4402 9ZM9 12.5L7 12.5L7 15.5L9 15.5L9 12.5ZM17 12.5L15 12.5L15 15.5L17 15.5L17 12.5Z");
  stroke: none;
}

.zggqekb1z {
  d: path("M5.35177 9L2.5 9M18.6482 9L21.5 9");
}

</style>
