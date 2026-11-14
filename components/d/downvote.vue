<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nazro8bps"/><path class="ap2ma41lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:downvote" /></template>
<style>
.ap2ma41lb {
  d: path("M9 11.5v-7a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nazro8bps {
  d: path("M7.56 11.5h8.88a1.75 1.75 0 0 1 1.272 2.952l-4.44 4.701a1.75 1.75 0 0 1-2.544 0l-4.44-4.701A1.75 1.75 0 0 1 7.56 11.5");
}

</style>
