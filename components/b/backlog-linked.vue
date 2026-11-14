<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh9_9kbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backlog-linked" /></template>
<style>
.qh9_9kbtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h4.5A3.5 3.5 0 0 1 14 6.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 3m0 11h4.5a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 14M19.25 3za2.25 2.25 0 0 1 2.25 2.25v3.5A2.25 2.25 0 0 1 19.25 11A2.25 2.25 0 0 1 17 8.75v-3.5A2.25 2.25 0 0 1 19.25 3m0 6v6m0-2za2.25 2.25 0 0 1 2.25 2.25v3.5A2.25 2.25 0 0 1 19.25 21A2.25 2.25 0 0 1 17 18.75v-3.5A2.25 2.25 0 0 1 19.25 13");
}

</style>
