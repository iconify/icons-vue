<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m4bwz_n8r"/><path class="n0q0gac6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hospital-cafe" /></template>
<style>
.m4bwz_n8r {
  d: path("M11.497 16.462A3.97 3.97 0 0 1 9.5 17H7c-2.2 0-4-1.8-4-4V7.5h10.5V13q0 .378-.069.737M13.5 8.75h.75c1.25 0 2.25 1 2.25 2.25q0 .22-.04.427M6.25 5.5c-1-1.25 1-2.25 0-3.5m4 3.5c-1-1.25 1-2.25 0-3.5");
}

.n0q0gac6b {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
