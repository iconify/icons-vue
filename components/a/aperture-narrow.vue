<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ewwenw0ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aperture-narrow" /></template>
<style>
.ewwenw0ef {
  d: path("m13.575 12.744l-.143.25a1.5 1.5 0 0 1-1.302.756h-.26a1.5 1.5 0 0 1-1.302-.756l-.143-.25a1.5 1.5 0 0 1 0-1.488l.143-.25a1.5 1.5 0 0 1 1.302-.756h.26a1.5 1.5 0 0 1 1.302.756l.143.25a1.5 1.5 0 0 1 0 1.488M14 12l4.25 7.25M13 13.75L8.75 21M11 13.75H2.75M10 12L5.75 4.75m5.25 5.5L15.25 3M13 10.25h8.25");
}

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

</style>
