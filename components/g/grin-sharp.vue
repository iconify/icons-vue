<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="wfdnybbtq"/><path class="hg3qm5bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grin-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hg3qm5bjr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13.25h8.5a4.25 4.25 0 0 1-8.5 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wfdnybbtq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M15 10h.01");
}

</style>
