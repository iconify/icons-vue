<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkza5fb9k"/><path class="dfdk8qbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contractor" /></template>
<style>
.dfdk8qbbq {
  d: path("M17.25 16.75v-1.5h2.5v1.5");
}

.tkza5fb9k {
  d: path("M4.5 10a7.5 7.5 0 0 1 15 0m-5.1 2.5H2.5V10h19v2.4M10 10V2.75M14 10V2.75M15.5 16h6v6h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
