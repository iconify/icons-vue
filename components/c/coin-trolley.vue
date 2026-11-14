<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zpb7h0btk"/><path class="vm759yqbq"/><path class="m-9_tz5_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coin-trolley" /></template>
<style>
.m-9_tz5_l {
  d: path("M16.25 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm759yqbq {
  d: path("M2 3h2l2.75 11.5H10m-4.5 4.25h.01m3.99 0h.01m3.99-1a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

.zpb7h0btk {
  d: path("M15.74 11H6.25l-1.5-5.5H19.5l-1.186 5.217");
}

</style>
