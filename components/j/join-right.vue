<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sos3x00pq"/><path class="tmzo-kb_u"/><path class="k31ioubfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:join-right" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k31ioubfu {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m7-2.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m0 5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.sos3x00pq {
  d: path("M2 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.tmzo-kb_u {
  d: path("M10 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
