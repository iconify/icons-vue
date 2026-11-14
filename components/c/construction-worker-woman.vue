<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vc409hb3z"/><path class="mn9n351vz"/><path class="d9x2debob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:construction-worker-woman" /></template>
<style>
.d9x2debob {
  d: path("M9.25 16.75L12 20l2.75-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mn9n351vz {
  d: path("M15 10.75c2.5.25 3.25 1.75 2.75 3.25M4.5 21.5c0-3 3.25-5.25 7.5-5.25s7.5 2.25 7.5 5.25");
}

.vc409hb3z {
  d: path("M6 7.5h12m-10 0a4 4 0 0 1 8 0m-7.5 0V9a3.5 3.5 0 0 0 7 0V7.5");
}

</style>
