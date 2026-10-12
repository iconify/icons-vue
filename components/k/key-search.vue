<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><circle class="e9pwlacgz"/><path class="gi6lp8bso"/><path class="ssv44kbxz"/></g><path class="m-fq38bof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-search" /></template>
<style>
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

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.m-fq38bof {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 16.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.5 2L20 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ssv44kbxz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 12.25l8.5-8.5m-3 3L19.5 9m-4.75.25L16.5 11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
