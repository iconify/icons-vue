<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qklo8fpey"/><path class="sj24qbb8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:json-viewer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qklo8fpey {
  d: path("M7 3.5Q4.5 3.5 4.5 6v4q0 2-2 2q2 0 2 2v4q0 2.5 2.5 2.5m10-17q2.5 0 2.5 2.5v4q0 2 2 2q-2 0-2 2v4q0 2.5-2.5 2.5M8 12c1-2.25 2.5-3.25 4-3.25s3 1 4 3.25c-1 2.25-2.5 3.25-4 3.25s-3-1-4-3.25");
}

.sj24qbb8h {
  fill: currentColor;
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
