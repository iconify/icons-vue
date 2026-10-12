<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sx5sr-pck"/><path class="zwzac24_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bmx" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sx5sr-pck {
  d: path("M2.75 17.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.zwzac24_t {
  d: path("M6 17.75h5.75L10 13.25l6.85-1l-5.1 5.5M10 13.25L9.25 11M8 11h2.5m7.5 6.75L15.25 4.5h-2m3.11.8l2.14-.5q.88-.2 1.08.68l.41 1.74q.2.88-.68 1.08l-2.14.5q-.88.2-1.08-.68l-.41-1.74q-.2-.88.68-1.08");
}

</style>
