<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="eh67qx3yv"/><path class="h9qa0mbnm"/><path class="osdxkeb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-devil" /></template>
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

.osdxkeb2q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 10l2 .9m5-.9l-2 .9m-4.75 5.35c2 1.5 4.5 1.5 6.5 0M5 7.75c-1.6-1-2.25-2.75-2-5c1 1.25 2.5 2 4.25 2Zm14 0c1.6-1 2.25-2.75 2-5c-1 1.25-2.5 2-4.25 2Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
