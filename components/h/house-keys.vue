<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byq9aveoo"/><path class="qua15d-7o"/><path class="p0cm-lbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-keys" /></template>
<style>
.byq9aveoo {
  d: path("M3 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-.5 9L5 12.5L7.5 15v6h-5zm3-5.75L5 12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0cm-lbhm {
  d: path("M8.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 11l7 7m-2.75-2.75L15 16.5m4 1.5l-1.25 1.25");
}

.qua15d-7o {
  d: path("M9.5 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h8m-3 0v2m2.5-2v2");
}

</style>
