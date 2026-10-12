<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mguy0_0ot"/><path class="ej1e9f33a"/><path class="u1k-zbcxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accordion-sharp" /></template>
<style>
.ej1e9f33a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 7.25l2.13-1.5L12 7.25l2.13-1.5l2.12 1.5v9.5l-2.12 1.5l-2.13-1.5l-2.12 1.5l-2.13-1.5Z");
}

.mguy0_0ot {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h5v12.5h-5zm13.5 0h5v12.5h-5z");
}

.u1k-zbcxv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 9v.01m0 2.99v.01m0 2.99v.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
