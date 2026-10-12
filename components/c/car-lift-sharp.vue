<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o8ztydlqn"/><circle class="uay-wcchm"/><path class="yngw34bnt"/><circle class="ugmgryb8x"/><path class="rpxachbmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-lift-sharp" /></template>
<style>
.o8ztydlqn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3v18M20 3v18M2.75 21h18.5M4 15h16M7 10.25V9l.74-.11l.27-.03l.74-.11l.45-.6l.6-.8l.45-.6h4.5l.45.6l.6.8l.45.6l.38.13L17 9v2H7z");
}

.rpxachbmq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 13h.01");
}

.uay-wcchm {
  cx: 9px;
  cy: 13px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ugmgryb8x {
  cx: 15px;
  cy: 13px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yngw34bnt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 13h.01");
}

</style>
