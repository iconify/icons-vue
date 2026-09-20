<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l2x-_sd5q"/><path class="xcjkf-bzr"/><path class="id5fryblw"/><path class="wa8tqsbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:holdout-group-outline-bold" /></template>
<style>
.id5fryblw {
  d: path("M15.5 4v16");
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wa8tqsbro {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xcjkf-bzr {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
