<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sm5my-bsd"/><path class="g6cazd-ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:color-blind-mode-sharp" /></template>
<style>
.g6cazd-ju {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 7.5h.01m2.99 0h.01m5.99 0h.01m-9.01 3h.01m8.99 0h.01m-9.01 3h.01m2.99 0h.01m5.99 0h.01m-9.01 3h.01m2.99 0h.01m5.99 0h.01m-3.01-9h.01m-.01 3h.01m-.01 3h.01m-.01 3h.01m-3.01-6h.01");
}

.sm5my-bsd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 9.25 0 1 0 18.5 0a9.25 9.25 0 1 0-18.5 0");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
