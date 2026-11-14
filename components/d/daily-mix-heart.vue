<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u01tthbal"/><path class="j5ia-o6vj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:daily-mix-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5ia-o6vj {
  d: path("M9 14a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0m4 0V9.25");
}

.u01tthbal {
  d: path("M12 20.5C6 16 3 12.5 3 9c0-3 2.25-5 4.75-5c2 0 3.5 1.25 4.25 2.75c.75-1.5 2.25-2.75 4.25-2.75C18.75 4 21 6 21 9c0 3.5-3 7-9 11.5");
}

</style>
