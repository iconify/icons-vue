<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ywc7vmbge"/><path class="g-nttibir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drawer" /></template>
<style>
.g-nttibir {
  d: path("M3.25 8.75h17.5m-17.5 5.5h17.5M10.5 6h3m-3 5.5h3m-3 5.4h3M6 19.5v1.75m12-1.75v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywc7vmbge {
  width: 17.5px;
  height: 16.25px;
  x: 3.25px;
  y: 3.25px;
  rx: 2px;
}

</style>
