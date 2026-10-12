<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p08n-yb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hedge-trimmer" /></template>
<style>
.p08n-yb5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.48 8.68l3.54.64q.98.18.98 1.18v3q0 1-.98 1.18l-3.54.64q-.98.18-.98-.82v-5q0-1 .98-.82M5.5 9.75H3.75a1 1 0 0 0-1 1v2.5a1 1 0 0 0 1 1H5.5M11 10.5l1.46-2l1.46 2l1.46-2l1.46 2l1.46-2l1.46 2a1.5 1.5 0 0 1 0 3l-1.46 2l-1.46-2l-1.46 2l-1.46-2l-1.46 2l-1.46-2Z");
}

</style>
