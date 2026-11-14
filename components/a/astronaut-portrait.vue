<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="h6hbdqbim"/><path class="lghzfr4id"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astronaut-portrait" /></template>
<style>
.h6hbdqbim {
  d: path("M7 17.5v-7a5 5 0 0 1 10 0v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lghzfr4id {
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-3 7.5c0-1.75 2.25-2.75 5-2.75s5 1 5 2.75");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
