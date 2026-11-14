<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5wh3h36c"/><path class="jdw2sfbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garbage-disposal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdw2sfbjf {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0m3.5-1.5l3 3m0-3l-3 3");
}

.n5wh3h36c {
  d: path("M11 3.5h2a8.5 8.5 0 0 1 8.5 8.5a8.5 8.5 0 0 1-8.5 8.5h-2A8.5 8.5 0 0 1 2.5 12A8.5 8.5 0 0 1 11 3.5");
}

</style>
