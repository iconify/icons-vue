<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tm0h1j8yt"/><path class="r5wi10bxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flood-rescue-boat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5wi10bxh {
  d: path("M17 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.tm0h1j8yt {
  d: path("M15.394 12H7L3 7.5h17.5a4.48 4.48 0 0 1-2.402 3.988M7 7.5V4h5.5l2 3.5M3 15q2.25-2 4.5 0t4.5 0m-9 4.5q2.25-2 4.5 0q2.091 1.858 4.181.263M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
