<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxrshwbpq"/><path class="ria_4ep6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-heart" /></template>
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

.ria_4ep6d {
  d: path("M12 17.5s-3-1.75-3-3.75c0-1 .75-1.75 1.75-1.75c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c1 0 1.75.75 1.75 1.75c0 2-3 3.75-3 3.75");
}

</style>
