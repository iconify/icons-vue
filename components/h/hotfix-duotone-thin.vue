<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="imqf40bqj"/><path class="ga-755bvs"/><path class="cr3csqnmb"/><path class="gljey2tgk"/><path class="pqzdmxnfr"/><path class="ygm75acdx"/><path class="wf5lx0b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotfix-duotone-thin" /></template>
<style>
.cr3csqnmb {
  fill: currentColor;
  d: path("M18 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ga-755bvs {
  fill: currentColor;
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gljey2tgk {
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imqf40bqj {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pqzdmxnfr {
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

.wf5lx0b1p {
  d: path("M18 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ygm75acdx {
  d: path("M19 2v3.5");
}

</style>
