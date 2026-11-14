<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpqsj0bcw"/><path class="q7pl131ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-curve-right" /></template>
<style>
.bpqsj0bcw {
  d: path("M5.5 20c0-7.5 5-12 13.5-12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7pl131ie {
  d: path("M15.5 4.5L19 8l-3.5 3.5");
}

</style>
