<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e958_-o_k"/><path class="qqda0pg3j"/><path class="c520s6bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-bus-sharp" /></template>
<style>
.c520s6bog {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9.75v2.5h2.5l.75 2m-4.85-3.4a2.25 2.25 0 1 0 3 3.25M14 8h4.25M14 8v6");
}

.e958_-o_k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.25h18.5v13H2.75zm2 13a2.5 2.5 0 0 0 5 0m4.5 0a2.5 2.5 0 0 0 5 0");
}

.qqda0pg3j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
