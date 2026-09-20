<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yyvm7xbin"/><path class="l-nryhbcn"/><path class="lo7kp72nh"/><path class="wmi7x3_7r"/><path class="m3koyfgfl"/><path class="pfndwmm4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handoff-duotone-regular" /></template>
<style>
.l-nryhbcn {
  fill: currentColor;
  d: path("M15 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.m3koyfgfl {
  d: path("M11 8h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfndwmm4f {
  d: path("m15 5 3 3 -3 3");
}

.wmi7x3_7r {
  d: path("M15 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.yyvm7xbin {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
