<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="th2y3uo2c"/><path class="h7cptgbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h7cptgbny {
  d: path("M3 12C3 10.8954 3.8954 10 5 10L7 10L7 21L5 21C3.8954 21 3 20.1046 3 19L3 12ZM21 12C21 10.8954 20.1046 10 19 10L17 10L17 21L19 21C20.1046 21 21 20.1046 21 19L21 12ZM3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12");
}

.th2y3uo2c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 10.4812 3.4812 9 5 9L7 9C7.5523 9 8 9.4477 8 10L8 21C8 21.5523 7.5523 22 7 22L5 22C3.4812 22 2 20.5188 2 19L2 12ZM22 12C22 10.4812 20.5188 9 19 9L17 9C16.4477 9 16 9.4477 16 10L16 21C16 21.5523 16.4477 22 17 22L19 22C20.5188 22 22 20.5188 22 19L22 12Z");
  stroke: none;
}

</style>
