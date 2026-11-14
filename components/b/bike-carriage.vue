<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bvdqn2u7p"/><path class="tq_agcilv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-carriage" /></template>
<style>
.bvdqn2u7p {
  d: path("M14.928 14.5H3.5q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T2.5 13.5V3q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 2h12q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T16.5 3v10.186");
}

.tq_agcilv {
  d: path("M5.5 4.75h8V8.5h-8Zm1 6.75h.01m5.99 0h.01m1.24 8a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m5.25 0a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m-3.75 0l2-3.5h2.5l.75 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
