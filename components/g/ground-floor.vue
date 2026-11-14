<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="upviaib9j"/><path class="t6khgnj_p"/><path class="v2r-s_jco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ground-floor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t6khgnj_p {
  fill: currentColor;
  d: path("M7.5 15h9a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 17.5v-1A1.5 1.5 0 0 1 7.5 15");
}

.upviaib9j {
  d: path("M6 15V8.5L12 3l6 5.5V15");
}

.v2r-s_jco {
  d: path("M2.5 21.5h19M6 10h12");
}

</style>
