<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wm3cirb_x"/><path class="dywmofmwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:high-ceiling" /></template>
<style>
.dywmofmwe {
  d: path("M8.75 14.5a3.25 3.25 0 0 1 6.5 0ZM12 16.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wm3cirb_x {
  d: path("M2.5 21.5V10L12 2.5l9.5 7.5v11.5M12 2.5v8.75");
}

</style>
