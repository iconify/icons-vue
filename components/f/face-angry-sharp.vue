<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="dd_6j-l0z"/><path class="vdnc73nzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-angry-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vdnc73nzx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 7.75l3 1.25m6.5-1.25l-3 1.25m-5 7.5l1.2-1.5h4.1l1.2 1.5");
}

</style>
