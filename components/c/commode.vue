<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1gqxtbeo"/><path class="lj0kzvbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commode" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj0kzvbbk {
  d: path("M8.25 13.5a3.75 1.25 0 1 0 7.5 0a3.75 1.25 0 1 0-7.5 0m-2.75 2l-1 6m14-6l1 6");
}

.s1gqxtbeo {
  d: path("M8.5 2.5h7A3.5 3.5 0 0 1 19 6a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 6a3.5 3.5 0 0 1 3.5-3.5m-4 11a7.5 3.5 0 1 0 15 0a7.5 3.5 0 1 0-15 0");
}

</style>
