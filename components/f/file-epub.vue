<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="e3onxpbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-epub" /></template>
<style>
.e3onxpbfh {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-7.25 4v6m0-6c-1-.75-2.25-1-3.75-1v6c1.5 0 2.75.25 3.75 1c1-.75 2.25-1 3.75-1v-6c-1.5 0-2.75.25-3.75 1");
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
