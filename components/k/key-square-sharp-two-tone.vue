<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y0z_wrb2k"/><path class="oyop0fbrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-square-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oyop0fbrw {
  d: path("M6 14.5L2 18.5L2 22L5.5 22L7 20.5L9.5 20.5L9.5 18L12 18L12 15.5L13.5 14L22 14L22 2L10 2L10 10.5ZM14.7071 9.2929L17.2929 6.7071");
}

.y0z_wrb2k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.2929 13.7929L1.2929 17.7929C1.1054 17.9804 1 18.2348 1 18.5L1 22C1 22.5523 1.4477 23 2 23L5.5 23C5.7652 23 6.0196 22.8946 6.2071 22.7071L7.4142 21.5L9.5 21.5C10.0523 21.5 10.5 21.0523 10.5 20.5L10.5 19L12 19C12.5523 19 13 18.5523 13 18L13 15.9142L13.9142 15L22 15C22.5523 15 23 14.5523 23 14L23 2C23 1.4477 22.5523 1 22 1L10 1C9.4477 1 9 1.4477 9 2L9 10.0858L5.2929 13.7929Z");
  stroke: none;
}

</style>
