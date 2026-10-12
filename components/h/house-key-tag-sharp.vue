<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qpb8uwt5b"/><path class="zubaqinwb"/><circle class="azfkbib2o"/><path class="c7x6ymbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:house-key-tag-sharp" /></template>
<style>
.azfkbib2o {
  cx: 15.75px;
  cy: 8.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.c7x6ymbwt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 11.25v10m0-4.75h2.5m-2.5 3h2");
}

.qpb8uwt5b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75a3 3 0 1 1 0 6a3 3 0 1 1 0-6M3.96 12.79l2.08-2.08l.71-.71l.71.71l2.08 2.08l.71.71v7.75h-7V13.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zubaqinwb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 14h.01");
}

</style>
