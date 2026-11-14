<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsr9tw65b"/><path class="kf7bfdb_x"/><path class="eb8ny4zms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:academic-calendar" /></template>
<style>
.eb8ny4zms {
  d: path("M9.25 14.5v2c0 1.75 5.5 1.75 5.5 0v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf7bfdb_x {
  d: path("m9.25 12.5l2.237-.814a1.5 1.5 0 0 1 1.026 0l2.237.814a1.064 1.064 0 0 1 0 2l-2.237.814a1.5 1.5 0 0 1-1.026 0L9.25 14.5a1.064 1.064 0 0 1 0-2");
}

.rsr9tw65b {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.25A4.375 4.375 0 0 1 7.375 4.5M3 8.75h18M8 2.5v4m8-4v4");
}

</style>
