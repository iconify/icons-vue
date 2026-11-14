<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjysgebxu"/><path class="a-8mpc6kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emoji-angry" /></template>
<style>
.a-8mpc6kb {
  d: path("M8.5 17c1-1.25 2.1-1.75 3.5-1.75s2.5.5 3.5 1.75");
}

.fjysgebxu {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 11h.01M15 11h.01M7 7.5L10 9m7-1.5L14 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
