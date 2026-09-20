<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_k2t6-nh"/><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="r2dk7difb"/><path class="mpjzdqbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:farewell-duotone-thin" /></template>
<style>
.f69zonn4h {
  d: path("M4 17a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_k2t6-nh {
  fill: currentColor;
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mpjzdqbcl {
  d: path("m18 10 2 2 -2 2");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.r2dk7difb {
  d: path("M14 12h6");
}

</style>
