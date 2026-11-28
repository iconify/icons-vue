<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y6v2gcbyu"/><path class="ch-5cdzrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iframe-off-sharp-two-tone" /></template>
<style>
.ch-5cdzrb {
  d: path("M21 21H3V3M3 9H9M17 17H7V13H13M1.707 1.707L22.293 22.293");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y6v2gcbyu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.707 21.707C21.526 21.888 21.276 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.724 2.112 2.474 2.293 2.293L3 3V9H9L21.707 21.707ZM5.743 2H12H21C21.552 2 22 2.448 22 3V18.257L5.743 2Z");
  stroke: none;
}

</style>
