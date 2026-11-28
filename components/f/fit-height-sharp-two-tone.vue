<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qzkjrlbrg"/><path class="hksugzxov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-height-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hksugzxov {
  d: path("M4 2L20 2L20 22L4 22ZM12 6L12 18M8.7071 9.2929L12 6L15.2929 9.2929M8.7071 14.7071L12 18L15.2929 14.7071");
}

.qzkjrlbrg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1L20 1C20.5523 1 21 1.4477 21 2Z");
  stroke: none;
}

</style>
