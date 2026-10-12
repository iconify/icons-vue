<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bwg1gpx4h"/><path class="dr6ehfbdq"/><path class="kqd5ziwbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garden-shed-sharp" /></template>
<style>
.bwg1gpx4h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.46 8.67l15.08-4.09l1.21-.33v17H3.25V9z");
}

.dr6ehfbdq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12.75h3.5v3.5h-3.5zm6.5 8.5v-8.5h5v8.5");
}

.kqd5ziwbj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 17.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
