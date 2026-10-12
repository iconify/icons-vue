<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byw4s1ztq"/><path class="py95s0tuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-door" /></template>
<style>
.byw4s1ztq {
  d: path("m4.09 9.51l3.82-4.27q1.34-1.49 3.34-1.49h8q2 0 2 2v13.5q0 2-2 2H4.75q-2 0-2-2V13q0-2 1.34-3.49");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py95s0tuq {
  d: path("m7.44 9.77l2.62-2.79q.69-.73 1.69-.73h6q1 0 1 1V9.5q0 1-1 1h-10q-1 0-.31-.73M14.5 14h3");
}

</style>
