<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gxuhs93fa"/><path class="h7lkkj80i"/><path class="y6cjf5j_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clothes-tag" /></template>
<style>
.gxuhs93fa {
  d: path("M5.636 10.913V8.261a2.625 2.625 0 0 1 2.625-2.625h2.652a2.63 2.63 0 0 1 1.856.769l6.921 6.921a2.625 2.625 0 0 1 0 3.712l-2.652 2.652a2.625 2.625 0 0 1-3.712 0l-6.921-6.921a2.63 2.63 0 0 1-.769-1.856");
}

.h7lkkj80i {
  d: path("M7.25 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6cjf5j_m {
  d: path("M7.75 7.75C5 5 3 5 2.5 2.5");
}

</style>
