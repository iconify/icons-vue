<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8eameb9p"/><path class="kvj129bvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-sharp-two-tone" /></template>
<style>
.a8eameb9p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.6141 9.2108C21.8576 9.4003 22 9.6915 22 10L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 10C2 9.6915 2.1424 9.4003 2.3859 9.2108L11.3859 2.2071C11.747 1.926 12.253 1.926 12.6141 2.2071L21.6141 9.2108Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kvj129bvx {
  d: path("M21 10L12 2.9963L3 10L3 21L21 21L21 10ZM9 21L9 14L15 14L15 21");
}

</style>
