<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ws2kqxb6b"/><path class="mi3c1twbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-mister" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi3c1twbg {
  d: path("M10 8.5q0 3-1.5 4.5M4.75 3.75h.01m-.76 3h.01m.74 3h.01");
}

.ws2kqxb6b {
  d: path("M15 12h1a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-1a3.5 3.5 0 0 1-3.5-3.5v-2.5A3.5 3.5 0 0 1 15 12m-1.5 0V8.5h-6V5l3-1.75h7V12");
}

</style>
