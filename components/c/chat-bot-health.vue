<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bl8h7abjx"/><path class="v7fy4hivd"/><path class="cmq2ttc_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-bot-health" /></template>
<style>
.bl8h7abjx {
  d: path("M11.428 17H4.5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T3.5 16V7.5q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T4.5 6.5H17q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T18 7.5v3.886M10.75 6.5V4");
}

.cmq2ttc_y {
  d: path("M7.75 11.5h.01m5.99 0h.01m-11.26-1V13m11.75 5h1l1.25-2.5l1.75 5l1.5-2.5h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7fy4hivd {
  fill: currentColor;
  d: path("M9.75 3a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
