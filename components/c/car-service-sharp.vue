<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vg_dtubxa"/><circle class="k6r3zgz2g"/><circle class="i_laebm5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-service-sharp" /></template>
<style>
.i_laebm5d {
  cx: 14px;
  cy: 19.25px;
  r: 2px;
}

.k6r3zgz2g {
  cx: 6.75px;
  cy: 19.25px;
  r: 2px;
}

.vg_dtubxa {
  d: path("M20.5 8a3.5 3.5 0 1 1 0-3.5M18.75 4l1.75.5l.5-1.75M2.75 16.25V13.5l.97-.22l1.31-.31l.97-.22l.55-.83l.9-1.34l.55-.83h4.5l.55.83l.9 1.34l.55.83l.99.14l1.52.22l.99.14v4H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
