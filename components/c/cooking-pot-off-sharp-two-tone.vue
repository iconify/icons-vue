<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gq7c07bpk"/><path class="y_z9geb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gq7c07bpk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 11C3 10.4477 3.4477 10 4 10L10 10L21 21ZM21 12.0001L21 17.2574L15.7427 12.0001L15.6569 12.0001L15.6569 11.9143L13.7426 10L20 10C20.004 10 20.008 10 20.012 10.0001L23 10.0001L23 12.0001L21 12.0001ZM11.6569 7.9143L7 3.2574L7 3C7 2.4477 7.4477 2 8 2L16 2C16.5523 2 17 2.4477 17 3L17 6.0001L21 6.0001L21 8.0001L11.6569 8.0001L11.6569 7.9143Z");
  stroke: none;
}

.y_z9geb3p {
  d: path("M4 11L4 21L20 21L20 20M1 11L11 11M3 7L7 7M1.7071 1.7071L22.2929 22.2929");
}

</style>
