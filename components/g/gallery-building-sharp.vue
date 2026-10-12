<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a68zs_bjb"/><path class="h_qer25zh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gallery-building-sharp" /></template>
<style>
.a68zs_bjb {
  d: path("M2.75 6.5h18.5v14.75H2.75zm0-3h18.5");
}

.h_qer25zh {
  d: path("M7 10h10v7.5H7Zm0 7.5l3.25-3.25l2.25 2.25L14 15l3 2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
