<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="so8oqg5zt"/><path class="ow-_3609j"/><path class="f0oho4boy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:iv-drip" /></template>
<style>
.f0oho4boy {
  d: path("M7.5 13.25h9M12 16v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow-_3609j {
  fill: currentColor;
  d: path("M12 7.75c.75 1 1.25 1.5 1.25 2.25s-.5 1.25-1.25 1.25s-1.25-.5-1.25-1.25s.5-1.25 1.25-2.25");
}

.so8oqg5zt {
  d: path("M11 5.5h2A3.5 3.5 0 0 1 16.5 9v3.5A3.5 3.5 0 0 1 13 16h-2a3.5 3.5 0 0 1-3.5-3.5V9A3.5 3.5 0 0 1 11 5.5m1-3v3");
}

</style>
