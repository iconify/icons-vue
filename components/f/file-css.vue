<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="czmhhmb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-css" /></template>
<style>
.czmhhmb1l {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5M10 11a1.5 1.5 0 0 0-1.5 1.5v1A1.5 1.5 0 0 1 7 15a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 0 10 19m4-8a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 0 17 15a1.5 1.5 0 0 0-1.5 1.5v1A1.5 1.5 0 0 1 14 19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9wy2bsc {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

</style>
