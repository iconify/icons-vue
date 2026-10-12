<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v7g_znbsq"/><path class="u5gskybxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-check-sharp" /></template>
<style>
.u5gskybxs {
  d: path("M9.5 13.25L11.25 15l3.25-3.5");
}

.v7g_znbsq {
  d: path("M6.75 18.35a4 4 0 0 1-.55-7.96A5.75 5.75 0 0 1 16.85 9a4.5 4.5 0 0 1-.6 9.35Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
