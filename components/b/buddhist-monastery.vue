<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ezpxf5bgn"/><path class="llylxwbte"/><path class="h0c4bgbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buddhist-monastery" /></template>
<style>
.ezpxf5bgn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5h10q.5 0 .89.31l2.97 2.38q.39.31-.11.31H19.5q-.5 0-.5.5v8.75q0 .5-.5.5h-13q-.5 0-.5-.5V12q0-.5-.5-.5H3.25q-.5 0-.11-.31l2.97-2.38Q6.5 8.5 7 8.5m-2 3h14");
}

.h0c4bgbor {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25V18.5a1.5 1.5 0 0 1 3 0v2.75M9.25 8.5a2.75 2.75 0 0 1 5.5 0ZM12 5.75V3");
}

.llylxwbte {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15.25h.01m7.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
