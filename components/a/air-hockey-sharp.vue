<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="yngu-n7jp"/><path class="ed-xnxz9s"/><circle class="f4crteb_g"/><path class="nytdgjb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-hockey-sharp" /></template>
<style>
.ed-xnxz9s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12h.01");
}

.f4crteb_g {
  cx: 18px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nytdgjb7c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 9.25h2.5m-2.5 5.5h2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yngu-n7jp {
  cx: 6px;
  cy: 12px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
