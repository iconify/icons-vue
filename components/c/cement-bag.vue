<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aypj2acsh"/><rect class="pliglsbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cement-bag" /></template>
<style>
.aypj2acsh {
  d: path("M5.5 5.75h13l1.25 14a1.25 1.25 0 0 1-1.25 1.5h-13a1.25 1.25 0 0 1-1.25-1.5Zm0 0l1-3h11l1 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pliglsbcg {
  width: 8px;
  height: 6px;
  x: 8px;
  y: 11px;
  rx: 1px;
}

</style>
