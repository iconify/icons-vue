<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7mmbc3-c"/><path class="jdcw1mb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdcw1mb1z {
  d: path("m3.5 7.5l8.5 5l8.5-5m-8.5 5v9M7.75 5l8.5 5m0-5l-8.5 5");
}

.o7mmbc3-c {
  d: path("m12.887 3.022l6.75 3.971a1.75 1.75 0 0 1 .863 1.508v6.998a1.75 1.75 0 0 1-.863 1.508l-6.75 3.971a1.75 1.75 0 0 1-1.774 0l-6.75-3.971a1.75 1.75 0 0 1-.863-1.508V8.501a1.75 1.75 0 0 1 .863-1.508l6.75-3.971a1.75 1.75 0 0 1 1.774 0");
}

</style>
