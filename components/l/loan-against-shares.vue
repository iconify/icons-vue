<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5x6mf3_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-against-shares" /></template>
<style>
.q5x6mf3_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5v16M11.5 5v15.5m6-17.5v8.5M6 7za1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 6 15a1.5 1.5 0 0 1-1.5-1.5v-5A1.5 1.5 0 0 1 6 7m5.5 1.5zA1.5 1.5 0 0 1 13 10v4a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 10 14v-4a1.5 1.5 0 0 1 1.5-1.5m6-3.75za1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5m-.75 12.75h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
