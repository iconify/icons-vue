<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lu1_lacst"/><path class="joa1ztv3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-vertical-start-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.joa1ztv3m {
  d: path("M4 17L20 17M6 21L18 21");
}

.lu1_lacst {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 13C22 13.5523 21.5523 14 21 14L3 14C2.4477 14 2 13.5523 2 13L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

</style>
