<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gevq-ab6q"/><path class="biq5j1w-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-clock-sharp-two-tone" /></template>
<style>
.biq5j1w-d {
  d: path("M8.2889 21L3 21L3 5L21 5L21 8.2889M21 15.5C21 18.5376 18.5376 21 15.5 21C12.4624 21 10 18.5376 10 15.5C10 12.4624 12.4624 10 15.5 10C18.5376 10 21 12.4624 21 15.5ZM15 13.5L15 16L17.5 16M8 2L8 8M16 2L16 7.0147");
}

.gevq-ab6q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.2889 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 4.4477 2.4477 4 3 4L21 4C21.5523 4 22 4.4477 22 5L22 8.2889L20 8.2889C18.6502 7.4466 17.0911 7 15.5 7C10.8056 7 7 10.8056 7 15.5C7 17.0911 7.4466 18.6502 8.2889 20ZM22 15.5C22 19.0899 19.0899 22 15.5 22C11.9101 22 9 19.0899 9 15.5C9 11.9101 11.9101 9 15.5 9C19.0899 9 22 11.9101 22 15.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
