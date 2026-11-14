<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5o_ji60e"/><path class="wgfv0f-fs"/><path class="qiestibls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anniversary-rings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5o_ji60e {
  d: path("M3.5 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.qiestibls {
  d: path("m13.125 3.375l.176-.247a1.5 1.5 0 0 1 1.221-.628h.956a1.5 1.5 0 0 1 1.221.628l.176.247a1.39 1.39 0 0 1-.063 1.701l-.66.791a1.5 1.5 0 0 1-2.304 0l-.66-.791a1.39 1.39 0 0 1-.063-1.701");
}

.wgfv0f-fs {
  d: path("M9.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
