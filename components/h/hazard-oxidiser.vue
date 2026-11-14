<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrkh46bbk"/><path class="xt9ywwthk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-oxidiser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrkh46bbk {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.xt9ywwthk {
  d: path("M8 13.5c-1.5-3 .5-5.5 1.5-8q2.25 2.25 2.25 4.5C12.5 8 13.5 5.5 14 2.5c3 3 3.5 7.5 2 11");
}

</style>
