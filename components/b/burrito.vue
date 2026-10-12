<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ler0qmbty"/><path class="nxezfipuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burrito" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ler0qmbty {
  d: path("M6 7a6 4 0 0 1 12 0v4.75a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

.nxezfipuv {
  d: path("M9 7a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0m9 2.75c-2.5.25-4.5 1.25-5.75 3M6 15.5l1.5-1l1.5 1l1.5-1l1.5 1l1.5-1l1.5 1l1.5-1l1.5 1v4.75a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

</style>
