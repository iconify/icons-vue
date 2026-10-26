<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lwwv_tb_s"/><path class="zq1b-1b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-medical-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lwwv_tb_s {
  d: path("M8.25 6.5L8.25 3L15.75 3L15.75 6.5M2 6.5L22 6.5L22 21L2 21L2 6.5Z");
}

.zq1b-1b1c {
  fill: currentColor;
  d: path("M10.5 10L13.5 10L13.5 12.5L16 12.5L16 15.5L13.5 15.5L13.5 18L10.5 18L10.5 15.5L8 15.5L8 12.5L10.5 12.5Z");
  stroke: none;
}

</style>
