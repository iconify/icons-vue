<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jj32ut8if"/><path class="xgscl2bdj"/><path class="m8djw6c8f"/><path class="qrdjxcbap"/><path class="zirb-hbnv"/><path class="y_b-hlbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lobby-duotone-regular" /></template>
<style>
.jj32ut8if {
  fill: currentColor;
  d: path("M3 6v11h18V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m8djw6c8f {
  fill: currentColor;
  d: path("M13 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrdjxcbap {
  d: path("M3 6v11h18V6Z");
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y_b-hlbjs {
  d: path("M13 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
