<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="yk-tw5vst"/><path class="l7_3_8csi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-coins-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l7_3_8csi {
  d: path("M3 13L3 23M3 16.3L6.9326 12.7441C8.0716 11.7143 9.6664 11.35 11.171 11.6582L13.255 12.085M10.8771 14.4629L14.17 11.17C14.9511 10.389 16.219 10.389 17 11.17C17.7811 11.9511 17.7811 13.219 17 14L12 19L5 19L3 21");
}

.yk-tw5vst {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 16.3L6.9326 12.7441C8.0716 11.7143 9.6664 11.35 11.171 11.6582L13.255 12.085L14.17 11.17C14.9511 10.389 16.219 10.389 17 11.17C17.7811 11.9511 17.7811 13.219 17 14L12 19L5 19L3 21ZM22 4.5C22 6.433 20.433 8 18.5 8C16.567 8 15 6.433 15 4.5C15 2.567 16.567 1 18.5 1C20.433 1 22 2.567 22 4.5ZM9.5 5.5C9.5 7.433 7.933 9 6 9C4.067 9 2.5 7.433 2.5 5.5C2.5 3.567 4.067 2 6 2C7.933 2 9.5 3.567 9.5 5.5Z");
  stroke: none;
}

</style>
