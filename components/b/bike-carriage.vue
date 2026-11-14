<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr46ymgjd"/><path class="kfs2xcc3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-carriage" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfs2xcc3t {
  d: path("M7.25 4.75h4.5A1.75 1.75 0 0 1 13.5 6.5v.25a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 5.5 6.75V6.5a1.75 1.75 0 0 1 1.75-1.75M6.5 11.5h.01m5.99 0h.01m1.24 8a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m5.25 0a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m-3.75 0l2-3.5h2.5l.75 3.5");
}

.xr46ymgjd {
  d: path("M7.75 2h3.5a5.25 5.25 0 0 1 5.25 5.25v2a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 2.5 9.25v-2A5.25 5.25 0 0 1 7.75 2");
}

</style>
