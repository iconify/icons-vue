<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q1oy59b8h"/><path class="m25x4yb1c"/><path class="ak9rggbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loyalty-points-sharp" /></template>
<style>
.ak9rggbmc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 10h.01m3.49 0h.01M14 14h.01m3.49 0h.01");
}

.m25x4yb1c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.39 9.07l.69 1.53l.14.32l.35.03l1.66.18l.35.04l-.26.23l-1.24 1.13l-.26.23l.07.34l.35 1.64l.07.34l-.31-.17l-1.45-.84l-.3-.17l-.3.17l-1.45.84l-.31.17l.07-.34l.35-1.64l.07-.34l-.26-.23l-1.24-1.13l-.26-.23l.35-.04l1.66-.18l.35-.03l.14-.32l.69-1.53l.14-.32z");
}

.q1oy59b8h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
