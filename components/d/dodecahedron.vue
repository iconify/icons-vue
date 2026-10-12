<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vwu_a_0pb"/><path class="h0s3k6l1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dodecahedron" /></template>
<style>
.h0s3k6l1w {
  d: path("m12.81 8.09l2.9 2.1q.81.59.5 1.54l-1.11 3.41q-.31.95-1.31.95h-3.58q-1 0-1.31-.95l-1.11-3.41q-.31-.95.5-1.54l2.9-2.1q.81-.59 1.62 0M12 6.5V3.4m5.47 7.07l2.71-1.13m-4.8 7.56l1.67 2.06M8.62 16.9l-1.67 2.06m-.42-8.49L3.82 9.34");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwu_a_0pb {
  d: path("m13.19 2.99l3.15 1.02q1.19.39 1.92 1.4l1.95 2.67q.73 1.02.73 2.27v3.3q0 1.25-.73 2.27l-1.95 2.67q-.73 1.01-1.92 1.4l-3.15 1.02q-1.19.39-2.38 0l-3.15-1.02q-1.19-.39-1.92-1.4l-1.95-2.67q-.73-1.02-.73-2.27v-3.3q0-1.25.73-2.27l1.95-2.67q.73-1.01 1.92-1.4l3.15-1.02q1.19-.39 2.38 0");
}

</style>
