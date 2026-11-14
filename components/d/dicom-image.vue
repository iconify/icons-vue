<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zktcezbhz"/><path class="xr0mygkzk"/><path class="kjo29pziq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dicom-image" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjo29pziq {
  d: path("M8.5 6V5c0-1.1.9-2 2-2H19c1.1 0 2 .9 2 2v8.5c0 1.1-.9 2-2 2h-1m-12.25-.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.xr0mygkzk {
  d: path("M5.5 9V8c0-1.1.9-2 2-2H16c1.1 0 2 .9 2 2v8.5c0 1.1-.9 2-2 2h-1");
}

.zktcezbhz {
  d: path("M6 9h5.5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-5.5A3.5 3.5 0 0 1 6 9");
}

</style>
