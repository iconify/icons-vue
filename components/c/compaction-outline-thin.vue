<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfto2zbdp"/><path class="xlz01ub4s"/><path class="ml5vh8o3m"/><path class="n_1n94xtx"/><path class="ztxj-4b5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compaction-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml5vh8o3m {
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n_1n94xtx {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

.tfto2zbdp {
  d: path("M5 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xlz01ub4s {
  d: path("M11 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ztxj-4b5g {
  d: path("M6 17a2.5 2.5 0 0 1 2.5 -2.5h7A2.5 2.5 0 0 1 18 17a2.5 2.5 0 0 1 -2.5 2.5h-7A2.5 2.5 0 0 1 6 17");
}

</style>
