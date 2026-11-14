<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kg9g05deg"/><path class="m0s1iicze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ab-test" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kg9g05deg {
  d: path("M6 4.5h1.5A3.5 3.5 0 0 1 11 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5m10.5 0H18A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5h-1.5A3.5 3.5 0 0 1 13 16V8a3.5 3.5 0 0 1 3.5-3.5");
}

.m0s1iicze {
  d: path("m4.5 15l2.25-6L9 15m-3.75-2h3m7.25-4v6m0-6h2.25a1.5 1.5 0 0 1 0 3H15.5m0 0H18a1.5 1.5 0 0 1 0 3h-2.5");
}

</style>
