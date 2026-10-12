<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jtigl5b4a"/><path class="qh8-e9n5t"/><path class="vshhi9b5k"/><circle class="td69qzbgx"/><circle class="c-nzzb3th"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hamster-sharp" /></template>
<style>
.c-nzzb3th {
  cx: 18px;
  cy: 14.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtigl5b4a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5L7.375 4H9.75l.5 1c.6-.15 1.15-.25 1.75-.25s1.15.1 1.75.25l.5-1h2.375L17 5.5c2 1.5 3.25 4 3.25 7.25c0 4.75-3.5 8-8.25 8s-8.25-3.25-8.25-8C3.75 9.5 5 7 7 5.5Z");
}

.qh8-e9n5t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 9.75h.01m5.49 0h.01");
}

.td69qzbgx {
  cx: 6px;
  cy: 14.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vshhi9b5k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 11.75h1.5l-.75.75Zm.75.75v1m0 0l-.75.75l-1-.5M12 13.5l.75.75l1-.5");
}

</style>
