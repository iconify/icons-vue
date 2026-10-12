<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwvxecc6k"/><path class="yibdcrvyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invoice-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwvxecc6k {
  d: path("M5.5 2.75h13q.75 0 .75.75v17q0 .75-.64.35l-1.12-.7q-.64-.4-1.28-.01l-1.17.72q-.64.39-1.28-.01l-1.12-.7q-.64-.4-1.28 0l-1.12.7q-.64.4-1.28.01l-1.17-.72q-.64-.39-1.28.01l-1.12.7q-.64.4-.64-.35v-17q0-.75.75-.75M8 7h8m-8 3.5h3");
}

.yibdcrvyx {
  d: path("M15 10.5q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

</style>
