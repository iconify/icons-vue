<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ihtk6mbsb"/><rect class="p-vvb8bwy"/><path class="c1ny1t7ee"/><path class="zyi9fdcvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:impressions" /></template>
<style>
.c1ny1t7ee {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13.75c1-1.75 2.5-2.75 4.5-2.75s3.5 1 4.5 2.75c-1 1.75-2.5 2.75-4.5 2.75s-3.5-1-4.5-2.75");
}

.ihtk6mbsb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h12a3 3 0 0 1 3 3v12");
}

.p-vvb8bwy {
  width: 15px;
  height: 15px;
  x: 2.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zyi9fdcvr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 13.75h.01");
}

</style>
