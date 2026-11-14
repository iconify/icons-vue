<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hys5v5qdk"/><path class="h6o17_myy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:football-kids" /></template>
<style>
.h6o17_myy {
  d: path("m10.382 8.892l.98.712a1.5 1.5 0 0 1 .541 1.688l-.311.932a1.5 1.5 0 0 1-1.423 1.026H8.831a1.5 1.5 0 0 1-1.423-1.026l-.311-.932a1.5 1.5 0 0 1 .541-1.688l.98-.712a1.5 1.5 0 0 1 1.764 0M9.5 8.25V4.5m2.75 5.75l3.5-1m-4.5 4l2 3m-5.5-3l-2 3m1-6l-3.5-1m13.939 9.259l.436-1.259a1.19 1.19 0 0 1 2.25 0l.436 1.259a1.5 1.5 0 0 1-1.418 1.991h-.286a1.5 1.5 0 0 1-1.418-1.991");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hys5v5qdk {
  d: path("M3 11a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m-.5 9.5h19");
}

</style>
