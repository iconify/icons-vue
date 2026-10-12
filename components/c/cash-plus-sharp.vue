<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aa0k9nbrp"/><circle class="m6jsykbla"/><path class="bq7hn8bxr"/><path class="jg3mm4bct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cash-plus-sharp" /></template>
<style>
.aa0k9nbrp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v11.5H2.75z");
}

.bq7hn8bxr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 10.5h.01m12.49 0h.01");
}

.jg3mm4bct {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 19.25h13.5");
}

.m6jsykbla {
  cx: 12px;
  cy: 10.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
