<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cz-3yo7et"/><path class="g3y-ujbgh"/><path class="x09b5kb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dormer-window" /></template>
<style>
.cz-3yo7et {
  d: path("m7.5 12.5l-5 8h19l-5-8");
}

.g3y-ujbgh {
  d: path("M7.5 17.5V9L12 4.5L16.5 9v8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x09b5kb6n {
  d: path("M11.75 10h.5a1.5 1.5 0 0 1 1.5 1.5V13a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
