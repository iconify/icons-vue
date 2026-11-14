<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-d13hb-w"/><path class="h2mivromn"/><path class="qva9xyvgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forecast-calendar" /></template>
<style>
.h2mivromn {
  d: path("M11.25 12.25a2 2 0 1 0-1.5 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-d13hb-w {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.25A4.375 4.375 0 0 1 7.375 4.5m.125-2v4m9-4v4");
}

.qva9xyvgb {
  d: path("M9.75 17.75h5.5a1.5 1.5 0 0 0 0-3a2.75 2.75 0 0 0-5.5 0a1.5 1.5 0 0 0 0 3");
}

</style>
