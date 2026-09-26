<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vqx7nhbrs"/><path class="ffsthac_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:archive-sharp-two-tone" /></template>
<style>
.ffsthac_t {
  d: path("M2 4L22 4L22 9L2 9L2 4ZM4 9L4 20L20 20L20 9M9 13L15 13");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vqx7nhbrs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 9C23 9.5523 22.5523 10 22 10L2 10C1.4477 10 1 9.5523 1 9L1 4C1 3.4477 1.4477 3 2 3ZM4 8L20 8C20.5523 8 21 8.4477 21 9L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 9C3 8.4477 3.4477 8 4 8Z");
  stroke: none;
}

</style>
