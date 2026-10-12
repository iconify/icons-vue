<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="eh67qx3yv"/><path class="h9qa0mbnm"/><path class="m3xeaj_9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:devil-sharp" /></template>
<style>
.eh67qx3yv {
  cx: 12px;
  cy: 14px;
  r: 7px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.h9qa0mbnm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12.75h.01m4.99 0h.01");
}

.m3xeaj_9i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 10l2 .9m5-.9l-2 .9m-4.75 5.35L12 18.688l3.25-2.438M5 7.75c-1.6-1-2.25-2.75-2-5l1.6 2h2.65Zm14 0c1.6-1 2.25-2.75 2-5l-1.6 2h-2.65Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
