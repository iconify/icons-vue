<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bc1bqfbkj"/><path class="hscflvlbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-change-right" /></template>
<style>
.bc1bqfbkj {
  d: path("M2.5 2.5v19m19-19v19M12 2.5v4m0 11v4m-4 0V16c0-4 8-4 8-8V4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hscflvlbd {
  d: path("M13.25 6.75L16 4l2.75 2.75");
}

</style>
