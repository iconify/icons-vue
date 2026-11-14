<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="es_1dpb1z"/><path class="jtsuu3btv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earnest-money" /></template>
<style>
.es_1dpb1z {
  d: path("M2.5 5H5v8H2.5ZM19 10.9V5h2.5v8h-.6M19 6.5h-3.5L11 10c-.75.6-.5 1.75.5 1.75h1L15 10M5 6.5h3L10.25 8");
}

.jtsuu3btv {
  d: path("M5 11.5L9 15c.5.5 1.25.5 1.75 0l3.5-3h.925M20 16.25c-.25-.75-1-1.25-2-1.25c-1.1 0-1.75.6-1.75 1.5c0 1.75 3.75 1 3.75 3c0 .9-.75 1.5-2 1.5c-1 0-1.75-.5-2-1.25m2-6V15m0 6v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
