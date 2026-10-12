<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="vdix13b2o"/><circle class="g-f2a7b4r"/><path class="n4sag1rdu"/><path class="vbu8vkb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-handoff-sharp" /></template>
<style>
.g-f2a7b4r {
  cx: 17.5px;
  cy: 15px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4sag1rdu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 15h.01m2.49 0h.01m8.49 0h.01m2.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vbu8vkb9m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5q5-5 10 0m0-2v2h-2");
}

.vdix13b2o {
  cx: 6.5px;
  cy: 15px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
