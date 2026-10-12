<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2gkk7bbh"/><path class="mc2ru_bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:farmhouse" /></template>
<style>
.h2gkk7bbh {
  d: path("M2.75 20.25V12.2q0-1 .77-1.63l4.21-3.44q.77-.63 1.54 0l4.21 3.44q.77.63.77 1.63v8.05q0 1-1 1h-9.5q-1 0-1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mc2ru_bxr {
  d: path("M6.5 21.25v-5h4v5m-4-5l4 5m0-5l-4 5m10.25 0V7a2.25 2.25 0 0 1 4.5 0v14.25Zm0-10.25h4.5");
}

</style>
