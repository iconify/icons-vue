<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n9qngh_rl"/><path class="elmafvagc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chisel" /></template>
<style>
.elmafvagc {
  d: path("m10.65 9.87l5.77-5.77q.35-.35.82-.19l3.24 1.07q.47.16.12.51l-7.16 7.16q-.35.35-.7 0l-2.09-2.08q-.35-.35 0-.7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9qngh_rl {
  d: path("m10.92 10.82l1.56 1.56q1.41 1.41 0 2.82l-3.94 3.94q-1.41 1.41-2.83 0l-1.54-1.55q-1.42-1.41-.01-2.83l3.94-3.93q1.41-1.42 2.82-.01");
}

</style>
