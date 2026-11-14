<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p0j1gvx3c"/><path class="u6t7ilbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allergen-free-kitchen" /></template>
<style>
.p0j1gvx3c {
  d: path("M7.5 15.5v-3.25c-2-.5-3-2.35-2.5-4.25c.5-1.75 2.5-2.75 4.25-2C9.9 4.6 10.9 4 12 4s2.1.6 2.75 2c1.75-.75 3.75.25 4.25 2c.5 1.9-.5 3.75-2.5 4.25v3.25m-9 0h9V20h-9Z");
}

.u6t7ilbyk {
  d: path("m10.25 11.25l1.5 1.5l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
