<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o1zwk2a_d"/><path class="u_gnumbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:centriole" /></template>
<style>
.o1zwk2a_d {
  d: path("M9 4a3 1.5 0 1 0 6 0a3 1.5 0 1 0-6 0Zm0 0v6m6-6v6m-6 6v4a3 1.5 0 0 0 6 0v-4M5 10h13.5a1.5 3 0 0 1 0 6H5");
}

.u_gnumbtq {
  d: path("M3.5 13a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
