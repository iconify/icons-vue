<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="a0ccnsbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emergency-shower-sharp" /></template>
<style>
.a0ccnsbdj {
  d: path("M7 18.25v-12h5.5v1.5m-2.5 1h5M11 11v1.5m1.5-1.5v3m1.5-3v1.5");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
