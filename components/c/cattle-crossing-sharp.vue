<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu0a_bbmx"/><path class="se1r-8b6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cattle-crossing-sharp" /></template>
<style>
.se1r-8b6p {
  d: path("M8.5 13.25h5.25l.75-.5h.75V14l-1.5.5v1.25H8.5Zm.75 2.5v2m3.75-2v2m1.75-5l-.25-1");
}

.uu0a_bbmx {
  d: path("m12.98 4.99l7.29 13.02l.98 1.74H2.75l.98-1.74l7.29-13.02l.98-1.74z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
