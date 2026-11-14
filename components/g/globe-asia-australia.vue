<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="t441l9b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:globe-asia-australia" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.t441l9b4z {
  d: path("M12 2.5q-.144.112-.281.235m-1.065 17.288c.392.583.84 1.084 1.346 1.477m-.5-5.75l1-2.25l2.25-.75l.75 1.5l1-2.75l1.75 3l-1.5 2.25l-2.25-.5l-2.25 1.5Zm-6-3.5L6 9l2.25-2.5l2.75-1l3 .25l1.5 1.75l-2 1l-1 2L10 10l-1.75 2.25Z");
}

</style>
