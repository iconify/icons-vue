<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vnk0j1mhq"/><path class="f23hlqbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boulder" /></template>
<style>
.f23hlqbso {
  d: path("M15.5 5L13 12l8.5 7m-15 0L8 15.5L7 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnk0j1mhq {
  d: path("m2.5 19l2-8L9 6l6.5-1L20 9l1.5 10Z");
}

</style>
