<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kakdqpb5v"/><path class="o4kgdjrxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dive-site" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kakdqpb5v {
  d: path("M12 19c-3.5-4-6.5-7-6.5-10a6.5 6.5 0 0 1 13 0c0 3-3 6-6.5 10");
}

.o4kgdjrxh {
  d: path("M9.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-7 10q1.5-2 3 0t3 0m7 0q1.5-2 3 0t3 0");
}

</style>
