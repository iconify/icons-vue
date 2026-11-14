<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="orsfkvbyq"/><path class="df_if-bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airport-fire-station" /></template>
<style>
.df_if-bvg {
  d: path("M3.25 18.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M4.875 3.5h7.25A1.375 1.375 0 0 1 13.5 4.875a1.375 1.375 0 0 1-1.375 1.375h-7.25A1.375 1.375 0 0 1 3.5 4.875A1.375 1.375 0 0 1 4.875 3.5M7 3.5v2.75m3-2.75v2.75m8.5 8.25v7m-3-2.5l3-2.25l3 2.25M17 21.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.orsfkvbyq {
  d: path("M14.157 16.5H2.5V10q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 9h11v1.5h4l3 3v2.043");
}

</style>
