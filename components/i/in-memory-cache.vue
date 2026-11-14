<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g4e_094uf"/><path class="di1qfsbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:in-memory-cache" /></template>
<style>
.di1qfsbnu {
  d: path("M13 6.75L9.5 10.5H12l-1 2.75l3.5-3.75H12ZM6 16v3.5m4-3.5v3.5m4-3.5v3.5m4-3.5v3.5");
}

.g4e_094uf {
  d: path("M2.5 4h19v12h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
