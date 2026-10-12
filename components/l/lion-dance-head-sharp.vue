<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pbvadyxbr"/><path class="cykxfgb2d"/><path class="hgq5u2bur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion-dance-head-sharp" /></template>
<style>
.cykxfgb2d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 10.25h.01m5.49 0h.01");
}

.hgq5u2bur {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 14.25h8a4 3.25 0 0 1-8 0ZM3.75 9a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2m16.5-8a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2");
}

.pbvadyxbr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6V2.75M6 6h12v15.25H6z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
