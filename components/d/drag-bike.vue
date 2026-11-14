<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8h5vehvw"/><path class="ldw6an86d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drag-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldw6an86d {
  d: path("m6 13l5-4.5h5.5l2 4.5m-2-4.5l1-3M2.5 19h19");
}

.v8h5vehvw {
  d: path("M3 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0m12.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
