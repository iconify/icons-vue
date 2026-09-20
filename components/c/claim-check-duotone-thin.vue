<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g73h4zxmw"/><path class="hadc61b6e"/><path class="z0me3ob_n"/><path class="m7enui17k"/><path class="nnfdo4bja"/><path class="ihzr3_bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claim-check-duotone-thin" /></template>
<style>
.g73h4zxmw {
  fill: currentColor;
  d: path("M3 4h8l3 3 -3 3H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hadc61b6e {
  fill: currentColor;
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihzr3_bny {
  d: path("M8 16a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-9a2 2 0 0 1 -2 -2Z");
}

.m7enui17k {
  d: path("M3 4h8l3 3 -3 3H3Z");
}

.nnfdo4bja {
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z0me3ob_n {
  fill: currentColor;
  d: path("M8 16a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
