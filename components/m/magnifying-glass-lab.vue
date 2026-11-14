<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="polw-1gzh"/><path class="s7uxcdcgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnifying-glass-lab" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.polw-1gzh {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0m12 5l5 5");
}

.s7uxcdcgo {
  d: path("m8.379 10.854l2.475-2.475a1.25 1.25 0 0 1 1.767 0a1.25 1.25 0 0 1 0 1.767l-2.475 2.475a1.25 1.25 0 0 1-1.767 0a1.25 1.25 0 0 1 0-1.767");
}

</style>
