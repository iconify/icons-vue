<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c4unwbcyb"/><path class="vzhchmbsi"/><path class="jx7o7fb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adaptation" /></template>
<style>
.c4unwbcyb {
  d: path("M3.5 12a8.5 8.5 0 0 1 16-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx7o7fb4f {
  d: path("M3.75 18.75L4.5 16l2.75.75M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.vzhchmbsi {
  d: path("M20.25 5.25L19.5 8l-2.75-.75M20.5 12a8.5 8.5 0 0 1-16 4");
}

</style>
