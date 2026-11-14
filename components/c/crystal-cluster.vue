<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fu1isdbtj"/><path class="kitv04byd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crystal-cluster" /></template>
<style>
.fu1isdbtj {
  d: path("M3 20.5h18M9 19V7.5a1.5 1.5 0 0 1 .3-.9l1.5-2a1.5 1.5 0 0 1 2.4 0l1.5 2a1.5 1.5 0 0 1 .3.9V19a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 19m0-6l-2.5-2.5l-2 2.5v7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kitv04byd {
  d: path("M15 10.5L17.5 8l2 2.5v10");
}

</style>
