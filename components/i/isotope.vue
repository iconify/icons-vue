<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oxjri8bvi"/><path class="g8y_6jb6o"/><path class="u6v7fac-o"/><circle class="f2k4gu_jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:isotope" /></template>
<style>
.f2k4gu_jx {
  cx: 17.375px;
  cy: 10.52px;
  r: 2.25px;
}

.g8y_6jb6o {
  d: path("M6.63 14.89a2.25 2.25 0 0 1-.54-2.18a2.25 2.25 0 0 1-1.63-1.56m4.33 0a2.25 2.25 0 0 1-1.63 1.56a2.25 2.25 0 0 1-1.07 0m11.29 2.18a2.25 2.25 0 1 1-2.17-3.74a2.25 2.25 0 0 0 1.63 1.56a2.25 2.25 0 0 0 1.07 0a2.25 2.25 0 0 0 1.63-1.56a2.25 2.25 0 1 1-2.16 3.74");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oxjri8bvi {
  d: path("M4.46 11.15a2.25 2.25 0 1 1 4.33 0a2.25 2.25 0 1 1-2.16 3.74a2.25 2.25 0 1 1-2.17-3.74");
}

.u6v7fac-o {
  d: path("M17.38 14.89a2.25 2.25 0 0 1-.54-2.18");
}

</style>
