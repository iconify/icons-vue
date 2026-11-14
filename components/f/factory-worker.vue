<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x461y696e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:factory-worker" /></template>
<style>
.x461y696e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9c0-3.5 2.25-6 5-6s5 2.5 5 6M5 9h14M8.5 9v1.5a3.5 3.5 0 0 0 7 0V9m-11 12.5C4.5 19 7.75 17 12 17s7.5 2 7.5 4.5");
}

</style>
