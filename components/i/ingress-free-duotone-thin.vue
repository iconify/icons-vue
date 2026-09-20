<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vwu8g9_zw"/><path class="dfvjg5biy"/><path class="qo1-4gbes"/><path class="hmity-bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingress-free-duotone-thin" /></template>
<style>
.dfvjg5biy {
  d: path("M11 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

.hmity-bzw {
  d: path("M6 9.5 8.5 12 6 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo1-4gbes {
  d: path("M3 12h5.5");
}

.vwu8g9_zw {
  fill: currentColor;
  d: path("M11 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
