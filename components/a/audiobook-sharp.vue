<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h49cuzbld"/><path class="ltvtt3_sm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audiobook-sharp" /></template>
<style>
.h49cuzbld {
  d: path("m12 12.75l-1.528-1.25H8.5v8.25h1.972L12 21l1.528-1.25H15.5V11.5h-1.972zm0 0V21");
}

.ltvtt3_sm {
  d: path("M4.13 12.25v-1a7.87 7.87 0 0 1 15.74 0v1m-17.12 0H5.5v6.5H2.75zm15.75 0h2.75v6.5H18.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
