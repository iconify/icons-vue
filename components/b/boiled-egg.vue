<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="smcwfxl5b"/><path class="wr3-h-bha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boiled-egg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.smcwfxl5b {
  d: path("M12 3c4 0 6.5 5.5 6.5 10c0 4-2.75 7.5-6.5 7.5S5.5 17 5.5 13C5.5 8.5 8 3 12 3");
}

.wr3-h-bha {
  d: path("M9 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
