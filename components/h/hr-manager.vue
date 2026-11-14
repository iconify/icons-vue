<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qvzwfkorx"/><path class="wwqlhjb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hr-manager" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvzwfkorx {
  d: path("M2.5 21.5v-3C2.5 15 6 13 9.75 12.75L12 15.5l2.25-2.75C18 13 21.5 15 21.5 18.5v3Zm6-15a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.wwqlhjb4z {
  d: path("m12.5 16.375l.207.362a1.5 1.5 0 0 1 .158 1.088l-.365 1.55a.514.514 0 0 1-1 0l-.365-1.55a1.5 1.5 0 0 1 .158-1.088l.207-.362a.576.576 0 0 1 1 0M17.25 19c-1.25-.75-1.5-1.25-1.5-1.75q0-.75.75-.75c.25 0 .5.25.75.5c.25-.25.5-.5.75-.5q.75 0 .75.75c0 .5-.25 1-1.5 1.75");
}

</style>
