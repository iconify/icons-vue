<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kdybctn7p"/><path class="drs9macuz"/><path class="sp3ujwwyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-sharp-fill" /></template>
<style>
.drs9macuz {
  d: path("M12 8L12 3.5M1 14.5L4 14.5M23 14.5L20 14.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kdybctn7p {
  fill: currentColor;
  d: path("M4 7L20 7C20.5523 7 21 7.4477 21 8L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 8C3 7.4477 3.4477 7 4 7ZM10 12L8 12L8 13L10 13L10 12ZM16 12L14 12L14 13L16 13L16 12ZM9 16L9 18L15 18L15 16L9 16Z");
  stroke: none;
}

.sp3ujwwyq {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5Z");
  stroke: none;
}

</style>
