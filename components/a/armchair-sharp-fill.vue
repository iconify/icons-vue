<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="x57llxq7z"/><path class="p52tuibwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p52tuibwo {
  d: path("M19 20L19 22L19 23M5 20L5 22L5 23");
}

.x57llxq7z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 10.1707L3 2C3 1.4477 3.4477 1 4 1L12 1L20 1C20.5523 1 21 1.4477 21 2L21 10.1707C22.1652 10.5825 23 11.6937 23 13L23 20C23 20.5523 22.5523 21 22 21L19 21L12 21L5 21L2 21C1.4477 21 1 20.5523 1 20L1 13C1 11.6937 1.8348 10.5825 3 10.1707ZM12 3L5 3L5 10.1707C6.1652 10.5825 7 11.6938 7 13L17 13C17 11.6938 17.8348 10.5825 19 10.1707L19 3Z");
  stroke: none;
}

</style>
