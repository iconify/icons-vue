<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="qepuaqbvx"><circle class="e9pwlacgz"/><path class="gi6lp8bso"/><path class="ssv44kbxz"/></g><circle class="is-iy812x"/><path class="sob-b5brj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-clock-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.e9pwlacgz {
  cx: 8px;
  cy: 16px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gi6lp8bso {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16h.01");
}

.is-iy812x {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qepuaqbvx {
  stroke: currentColor;
}

.sob-b5brj {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v1.75l1.25 1");
}

.ssv44kbxz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 12.25l8.5-8.5m-3 3L19.5 9m-4.75.25L16.5 11");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

</style>
