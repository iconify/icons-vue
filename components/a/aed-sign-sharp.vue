<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="h7ytr2gzr"/><path class="wbr-aqbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aed-sign-sharp" /></template>
<style>
.h7ytr2gzr {
  d: path("M12 19s-6.75-3.75-6.75-8.25A3.4 3.4 0 0 1 12 8.85a3.4 3.4 0 0 1 6.75 1.9C18.75 15.25 12 19 12 19Z");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.wbr-aqbwt {
  d: path("m12.75 11.25l-2 2.75h2.5l-2 2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
