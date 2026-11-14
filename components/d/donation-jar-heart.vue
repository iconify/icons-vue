<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8mqnw7ac"/><path class="sqd2dab6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donation-jar-heart" /></template>
<style>
.c8mqnw7ac {
  d: path("M8 6.5h8v-4H8Zm2.5-2h3M8 6.5v1C5.5 8.5 5 10 5 12v7a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19v-7c0-2-.5-3.5-3-4.5v-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sqd2dab6d {
  d: path("m12 18l-2.75-2.75A2 2 0 0 1 12 12.5a2 2 0 0 1 2.75 2.75Z");
}

</style>
