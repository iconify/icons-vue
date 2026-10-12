<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w6c3afb2q"/><path class="uf1l71bgs"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-horizontal-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uf1l71bgs {
  stroke-opacity: 0.4;
  d: path("M15 3L21 3L21 7M21 9.5L21 14.5M21 17L21 21L15 21");
}

.w6c3afb2q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3C2 2.4477 2.4477 2 3 2L9 2L9 22L3 22C2.4477 22 2 21.5523 2 21L2 3Z");
  stroke: none;
}

.x1f4lc3zb {
  d: path("M12 2L12 22");
}

</style>
