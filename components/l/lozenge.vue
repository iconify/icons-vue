<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yuysgdcge"/><path class="wnsa9w01k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lozenge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnsa9w01k {
  d: path("m12.39 8.64l1.62 2.72q.39.64 0 1.28l-1.62 2.72q-.39.64-.78 0l-1.62-2.72q-.39-.64 0-1.28l1.62-2.72q.39-.64.78 0");
}

.yuysgdcge {
  d: path("m12.91 4l3.93 6.5q.91 1.5 0 3L12.91 20q-.91 1.5-1.82 0l-3.93-6.5q-.91-1.5 0-3L11.09 4q.91-1.5 1.82 0");
}

</style>
