<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><circle class="fw2awacyd"/><path class="gjm7u7v1y"/><path class="qyrds1bwu"/><path class="ea5fdbqox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:instant-photo-sharp" /></template>
<style>
.ea5fdbqox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.75h10.5");
}

.fw2awacyd {
  cx: 12px;
  cy: 11.25px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gjm7u7v1y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25h2.5");
}

.qyrds1bwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
