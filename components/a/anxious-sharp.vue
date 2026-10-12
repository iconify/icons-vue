<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="omkt26sjc"/><path class="dd_6j-l0z"/><path class="pxt3-fl_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anxious-sharp" /></template>
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

.omkt26sjc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.75L9.75 7.5m4.5 0L17 8.75");
}

.pxt3-fl_j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 16.75l1.1-1.1h2.8l1.1 1.1m3-6l1.25 1.833v.667a1.25 1.25 0 0 1-2.5 0v-.667z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
