<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n3_y-ybfy"/><path class="vugychrge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-heart-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n3_y-ybfy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 3L20 3C20.5523 3 21 3.4477 21 4L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.4477 3.4477 3 4 3L6 3L6 2C6 1.4477 6.4477 1 7 1L17 1C17.5523 1 18 1.4477 18 2Z");
  stroke: none;
}

.vugychrge {
  d: path("M7 4L4 4L4 22L20 22L20 4L17 4M7 2L17 2L17 7L7 7ZM12 18C10.175 16.4846 8 15.1806 8 13.2361C8 12.0011 9.0745 11 10.4 11C11 11 11.537 11.2123 12 11.5833C12.463 11.2123 13 11 13.6 11C14.9255 11 16 12.0011 16 13.2361C16 15.1806 13.825 16.4846 12 18Z");
}

</style>
