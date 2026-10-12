<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h4bbt32jz"/><path class="g7zl0zpdt"/><path class="d3djxwbgi"/><rect class="z_lnlobhg"/><path class="fukguacxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horse-stable" /></template>
<style>
.d3djxwbgi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 8.5h.01");
}

.fukguacxm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 13l11 8.25m0-8.25l-11 8.25");
}

.g7zl0zpdt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 13V9.75C9 8.25 10 7 11.5 6.5l.75-1.25L13 6.5c1.75.5 3.5 1.75 4.25 3.25c.25.75-.25 1-1 1h-2L13.5 13Z");
}

.h4bbt32jz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25V7L12 2.75L20.5 7v14.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_lnlobhg {
  width: 11px;
  height: 8.25px;
  x: 6.5px;
  y: 13px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
