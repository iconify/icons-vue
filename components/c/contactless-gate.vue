<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc-u5nu-s"/><path class="gpssa8yew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contactless-gate" /></template>
<style>
.gpssa8yew {
  d: path("M11.5 14h1a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 11.5 14M9.992 8.133a3.5 3.5 0 0 1 4.016 0M8.415 5.88a6.25 6.25 0 0 1 7.17 0M6.838 3.628a9 9 0 0 1 10.324 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tc-u5nu-s {
  d: path("M10.5 11h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18v-3.5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
