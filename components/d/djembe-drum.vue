<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jaiuwpblh"/><path class="b2cthrbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:djembe-drum" /></template>
<style>
.b2cthrbqz {
  d: path("M5 5c0 4.5 4.5 6 4.75 8.5L8 21.5h8l-1.75-8C14.5 11 19 9.5 19 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jaiuwpblh {
  d: path("M5 5a7 2.5 0 1 0 14 0A7 2.5 0 1 0 5 5");
}

</style>
