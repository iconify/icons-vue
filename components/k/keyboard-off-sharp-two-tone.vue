<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="fsv0zrbed"/><path clip-rule="evenodd" class="nbjsuy_7f"/><path class="fxazuu8bq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyboard-off-sharp-two-tone" /></template>
<style>
.fsv0zrbed {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3L3 3L21 21ZM6.7426 3L22 3C22.5523 3 23 3.4477 23 4L23 19.2574L6.7426 3Z");
  stroke: none;
}

.fxazuu8bq {
  d: path("M20 20L2 20L2 4L4 4M7 16L16 16M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nbjsuy_7f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7L15 7L15 9L13 9L13 7ZM17 7L19 7L19 9L17 9L17 7ZM5 11L7 11L7 13L5 13L5 11ZM17 11L19 11L19 13L17 13L17 11Z");
  stroke: none;
}

</style>
