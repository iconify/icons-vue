<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="f4ed35d8z"/><path class="nhicrdbao"/><path class="dwmbbpnte"/><path class="ey1hik3eo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dropper-bottle" /></template>
<style>
.dwmbbpnte {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.77 8.46l1.77 1.77q.53.53 0 1.06L12 14.83q-.53.53-1.23.79l-1.43.54q-.7.26-1.23-.27t-.27-1.23l.54-1.43q.26-.7.79-1.23l3.54-3.54q.53-.53 1.06 0");
}

.ey1hik3eo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.99 18.01H6");
}

.f4ed35d8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.24 4.58l.71-.71q1.06-1.06 2.12 0l1.06 1.06q1.06 1.06 0 2.12l-.71.71q-1.06 1.06-2.12 0L16.24 6.7q-1.06-1.06 0-2.12");
}

.nhicrdbao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.65 5.11l4.24 4.24q.71.71 0 1.41l-.7.71q-.71.71-1.42 0l-4.24-4.24q-.71-.71 0-1.42l.71-.7q.7-.71 1.41 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
