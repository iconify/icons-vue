<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6gbshblk"/><path class="jlmoznb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-cleaning" /></template>
<style>
.c6gbshblk {
  d: path("M10 4.5a2 2 0 1 1 2 2V8m2.85 13H6.5v-7.5l-2 1l-1.5-4L8.5 8h7l5.5 2.5l-.828 2.208");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlmoznb8q {
  d: path("M18.5 15q.5 2.75 3.25 3.25q-2.75.5-3.25 3.25q-.5-2.75-3.25-3.25Q18 17.75 18.5 15");
}

</style>
