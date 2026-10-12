<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mxdenudag"/><path class="s_0nod3fl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-vertical-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mxdenudag {
  fill: currentColor;
  d: path("M3 2C2.4477 2 2 2.4477 2 3L2 9L22 9L22 3C22 2.4477 21.5523 2 21 2L3 2Z");
  stroke: none;
}

.s_0nod3fl {
  d: path("M2 12L22 12M3 15L3 21L7 21M9.5 21L14.5 21M17 21L21 21L21 15");
}

</style>
