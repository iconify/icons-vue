<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nvwx38fgg"/><path class="p-o2-8bno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-0-100" /></template>
<style>
.nvwx38fgg {
  d: path("M9 13.5v-3L12 7h4l3.5 2.75l2 .75v3Z");
}

.p-o2-8bno {
  d: path("M10 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 8h3.75M3.5 11h2.75M2.5 14h3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
