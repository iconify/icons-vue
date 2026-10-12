<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vvaw43bcb"/><path class="u5elyyd1a"/><path class="jxx794e_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitesurf-sharp" /></template>
<style>
.jxx794e_c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 11.75L16.25 16m0 0l-2 2.4m2-2.4L18 17.8m-1.1-5.55h-4.25m-2.57 7.87l9.84-1.74");
}

.u5elyyd1a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 9.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vvaw43bcb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9c1-3.5 4-5.75 7.5-5.75c1.4 0 2.75.2 4 .5l-1 2.5c-1-.25-2-.25-3-.25c-2.25 0-4 1.25-5 3.75Zm2 1l7.5 3.75m1.5-8.5l-1 5.25m0 0l-.5 3.25");
}

</style>
