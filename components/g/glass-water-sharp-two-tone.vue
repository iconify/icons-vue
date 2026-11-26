<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s4fm2thhh"/><path class="m491jybai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glass-water-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m491jybai {
  d: path("M3.0016 2L20.9983 2L18 22L6 22ZM3.7441 6.9499C6.1187 6.0003 9.5425 6.017 12 7C14.4525 7.981 17.8674 7.9996 20.2413 7.0559");
}

.s4fm2thhh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.5119 12.1483L2.0127 2.1483C2.0053 2.0992 2.0016 2.0496 2.0016 2C2.0016 1.4477 2.4493 1 3.0016 1L20.9983 1C21.5506 1 21.9983 1.4477 21.9983 2C21.9983 2.0496 21.9946 2.0992 21.9872 2.1483L18.9889 22.1483C18.9156 22.6378 18.495 23 18 23L6 23C5.505 23 5.0844 22.6378 5.0111 22.1483Z");
  stroke: none;
}

</style>
