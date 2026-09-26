<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vfpcfvbpw"/><path class="r0b537ytf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0b537ytf {
  d: path("M3 14L10 14L10 21L3 21L3 14ZM3 3L10 3L10 10L3 10L3 3ZM14 14L21 14L21 21L14 21L14 14ZM14 3L21 3L21 10L14 10L14 3Z");
}

.vfpcfvbpw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L10 13C10.5523 13 11 13.4477 11 14L11 21C11 21.5523 10.5523 22 10 22L3 22C2.4477 22 2 21.5523 2 21L2 14C2 13.4477 2.4477 13 3 13ZM3 2L10 2C10.5523 2 11 2.4477 11 3L11 10C11 10.5523 10.5523 11 10 11L3 11C2.4477 11 2 10.5523 2 10L2 3C2 2.4477 2.4477 2 3 2ZM14 13L21 13C21.5523 13 22 13.4477 22 14L22 21C22 21.5523 21.5523 22 21 22L14 22C13.4477 22 13 21.5523 13 21L13 14C13 13.4477 13.4477 13 14 13ZM14 2L21 2C21.5523 2 22 2.4477 22 3L22 10C22 10.5523 21.5523 11 21 11L14 11C13.4477 11 13 10.5523 13 10L13 3C13 2.4477 13.4477 2 14 2Z");
  stroke: none;
}

</style>
