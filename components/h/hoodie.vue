<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chrtzg5rh"/><path class="ew4xwsbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoodie" /></template>
<style>
.chrtzg5rh {
  d: path("M10 5h4q1 0 1.92.39l1.66.72q.92.39 1.19 1.35l2.21 8.08q.27.96-.7 1.18l-1.31.31q-.97.22-.97 1.22v2q0 1-1 1H7q-1 0-1-1v-2q0-1-.97-1.22l-1.31-.31q-.97-.22-.7-1.18l2.21-8.08q.27-.96 1.19-1.35l1.66-.72Q9 5 10 5");
}

.ew4xwsbas {
  d: path("m9 5l3 4l3-4m-4.5 3.5V12m3-3.5V12M6 13v3.75M18 13v3.75m-9.5 4.5V18l1.5-2h4l1.5 2v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
