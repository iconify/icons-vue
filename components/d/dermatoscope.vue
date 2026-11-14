<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-_r0ybrc"/><path class="uqv4iccjw"/><path class="gxgr8ibya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dermatoscope" /></template>
<style>
.gxgr8ibya {
  fill: currentColor;
  d: path("M8.25 9.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-_r0ybrc {
  d: path("M3 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m11.422 4.922za1.75 1.75 0 0 1 2.474 0l3.182 3.182a1.75 1.75 0 0 1 0 2.474a1.75 1.75 0 0 1-2.474 0l-3.182-3.182a1.75 1.75 0 0 1 0-2.474");
}

.uqv4iccjw {
  d: path("M5.5 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
