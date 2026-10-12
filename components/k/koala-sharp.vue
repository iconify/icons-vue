<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zo44ht_1i"/><circle class="ghn-pjb3p"/><path class="mhiw94m_x"/><path class="p54w7vbgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:koala-sharp" /></template>
<style>
.ghn-pjb3p {
  cx: 12px;
  cy: 13.5px;
  r: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhiw94m_x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 15.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

.p54w7vbgf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 11.75h.01m6.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zo44ht_1i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.64 11.25a3 3 0 1 1 3.04-3.63a6.75 6.75 0 0 0-3.04 3.63Zm9.68-3.63a3 3 0 1 1 3.04 3.63a6.75 6.75 0 0 0-3.04-3.63Z");
}

</style>
