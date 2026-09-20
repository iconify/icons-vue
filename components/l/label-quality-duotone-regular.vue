<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbde_z08y"/><path class="r8hnofl7s"/><path class="pb8u2_oec"/><path class="w3hyiobto"/><path class="hgb-t7boy"/><path class="zf4ugsben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:label-quality-duotone-regular" /></template>
<style>
.fbde_z08y {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hgb-t7boy {
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pb8u2_oec {
  fill: currentColor;
  d: path("m12 11 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r8hnofl7s {
  fill: currentColor;
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

.zf4ugsben {
  d: path("m12 11 3 3 -3 3 -3 -3Z");
}

</style>
