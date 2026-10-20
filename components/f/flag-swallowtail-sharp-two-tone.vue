<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="adtc4bu-l"/><path class="zx8nlvbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-swallowtail-sharp-two-tone" /></template>
<style>
.adtc4bu-l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4C21 4.1612 20.961 4.32 20.8864 4.4629L17.9949 10L20.8864 15.5371C20.961 15.68 21 15.8388 21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16L3 4C3 3.4477 3.4477 3 4 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zx8nlvbfo {
  d: path("M4 1L4 23M4 4L20 4L16.8668 10L20 16L4 16");
}

</style>
