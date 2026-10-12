<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f15bztbfv"/><path class="pmua0m53g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chalk-line-sharp" /></template>
<style>
.f15bztbfv {
  d: path("M2.75 8.5h10.5v10H2.75z");
}

.pmua0m53g {
  d: path("M6 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-5v-3H5m8.25 8h5.5m0-2.25v4.5h2.5m-7.5 3h1.5m1.75 0h1.5m1.5 0h1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
