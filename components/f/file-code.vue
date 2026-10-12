<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="eqo9eibeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-code" /></template>
<style>
.eqo9eibeg {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-9 2.75A1.25 1.25 0 0 0 9 12.25v1a1 1 0 0 1-1 1a1 1 0 0 1 1 1v1a1.25 1.25 0 0 0 1.25 1.25m3.5-6.5A1.25 1.25 0 0 1 15 12.25v1a1 1 0 0 0 1 1a1 1 0 0 0-1 1v1a1.25 1.25 0 0 1-1.25 1.25");
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
