<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxrshwbpq"/><path class="lt2uogbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-user" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxrshwbpq {
  d: path("m5.195 9.454l4.5-3.937a3.5 3.5 0 0 1 4.61 0l4.5 3.937A3.5 3.5 0 0 1 20 12.088V16.5a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 16.5v-4.412a3.5 3.5 0 0 1 1.195-2.634");
}

.lt2uogbut {
  d: path("M10.5 11.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M9 18c.25-1.5 1.5-2.5 3-2.5s2.75 1 3 2.5");
}

</style>
