<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrvsxsgus"/><path class="snmfgfbqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-accelerator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrvsxsgus {
  d: path("M9.875 5.5h4.25A4.375 4.375 0 0 1 18.5 9.875v4.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 14.125v-4.25A4.375 4.375 0 0 1 9.875 5.5m-.375-3v3m5-3v3m-5 13v3m5-3v3m-12-12h3m-3 5h3m13-5h3m-3 5h3");
}

.snmfgfbqc {
  d: path("m11.959 9.69l-1.636 1.869a.567.567 0 0 0 .427.941a.9.9 0 0 1 .855 1.186L11.5 14a.318.318 0 0 0 .541.31l1.636-1.869a.567.567 0 0 0-.427-.941a.9.9 0 0 1-.855-1.186L12.5 10a.318.318 0 0 0-.541-.31");
}

</style>
