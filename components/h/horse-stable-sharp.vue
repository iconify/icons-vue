<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h4bbt32jz"/><path class="pg5agrxdg"/><path class="d3djxwbgi"/><path class="un438p27z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horse-stable-sharp" /></template>
<style>
.d3djxwbgi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 8.5h.01");
}

.h4bbt32jz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25V7L12 2.75L20.5 7v14.25");
}

.pg5agrxdg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 13V7.333l2.5-.833l.75-1.25L13 6.5c1.75.5 3.5 1.75 4.25 3.25l.333 1H14.25L13.5 13Z");
}

.un438p27z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13h11v8.25h-11zm0 0l11 8.25m0-8.25l-11 8.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
