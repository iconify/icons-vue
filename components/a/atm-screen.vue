<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6-grcbgu"/><path class="j-cjumblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-screen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-cjumblc {
  d: path("M9.5 6.25h5A1.75 1.75 0 0 1 16.25 8v3a1.75 1.75 0 0 1-1.75 1.75h-5A1.75 1.75 0 0 1 7.75 11V8A1.75 1.75 0 0 1 9.5 6.25M5.25 8.5h.01m-.01 4h.01m13.49-4h.01m-.01 4h.01m-8.26-3h3");
}

.s6-grcbgu {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14V7A3.5 3.5 0 0 1 6 3.5m6 14v3m-3.5 0h7");
}

</style>
