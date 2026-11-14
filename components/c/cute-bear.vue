<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo-wxdh9d"/><path class="kwi4ubc4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-bear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwi4ubc4e {
  d: path("M5 9.75a3 3 0 1 1 3.5-3.5M19 9.75a3 3 0 1 0-3.5-3.5M8.25 16a3.75 2.75 0 1 0 7.5 0a3.75 2.75 0 1 0-7.5 0M12 16h.01m-3.26-4.25h.01m6.49 0h.01");
}

.qo-wxdh9d {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

</style>
