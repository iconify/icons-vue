<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq743bcrl"/><path class="azs1qu6hv"/><path class="p7np2t4-r"/><path class="kk-ohg6gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crop-duotone-thin" /></template>
<style>
.azs1qu6hv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h16v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jq743bcrl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 2v16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kk-ohg6gv {
  d: path("M2 6h16v16");
}

.p7np2t4-r {
  d: path("M6 2v16h16");
}

</style>
