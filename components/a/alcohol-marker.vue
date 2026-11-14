<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kv10uwdlk"/><path class="a43-updlb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alcohol-marker" /></template>
<style>
.a43-updlb {
  d: path("m13.414 8.464l1.498-1.497a1.5 1.5 0 0 1 .637-.378l2.638-.776a.799.799 0 0 1 .79 1.331l-3.441 3.442a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122m-7.955 6.895l3.182 3.182");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kv10uwdlk {
  d: path("m3.868 16.95l6.364-6.364a2.25 2.25 0 0 1 3.182 0a2.25 2.25 0 0 1 0 3.182L7.05 20.132a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182");
}

</style>
