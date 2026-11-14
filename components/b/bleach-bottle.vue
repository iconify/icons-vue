<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hi5-4kb3u"/><path class="ga_eg6b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bleach-bottle" /></template>
<style>
.ga_eg6b2w {
  d: path("M12 11c1.5 1.75 2.75 3.5 2.75 5a2.75 2.75 0 0 1-5.5 0c0-1.5 1.25-3.25 2.75-5");
}

.hi5-4kb3u {
  d: path("M5 21.5V10l3-2.5h10A1.5 1.5 0 0 1 19.5 9v11a1.5 1.5 0 0 1-1.5 1.5Zm3.5-18h1A1.5 1.5 0 0 1 11 5v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 7 6V5a1.5 1.5 0 0 1 1.5-1.5m5.5 4v-3h3.5A1.5 1.5 0 0 1 19 6v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
