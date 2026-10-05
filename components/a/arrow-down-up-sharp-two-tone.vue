<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w9jhv2b_a"/><path class="poppadcki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-up-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.poppadcki {
  d: path("M6 2L6 3L6 21M2.7071 17.7071L3 18L6 21L9 18L9.2929 17.7071");
}

.w9jhv2b_a {
  stroke-opacity: 0.4;
  d: path("M18 22L18 21L18 3M14.7071 6.2929L15 6L18 3L21 6L21.2929 6.2929");
}

</style>
