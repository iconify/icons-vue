<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zqwlq2bsz"/><path class="nk8h9cc1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-notice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk8h9cc1f {
  d: path("M7 5.5h3.5A1.5 1.5 0 0 1 12 7v5a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 12V7A1.5 1.5 0 0 1 7 5.5m1.75 0h.01M7.25 9h3m-3 2.25h2M16 7h1a1.5 1.5 0 0 1 1.5 1.5V10a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V8.5A1.5 1.5 0 0 1 16 7");
}

.zqwlq2bsz {
  d: path("M4.25 3h15.5a1.75 1.75 0 0 1 1.75 1.75v9.5A1.75 1.75 0 0 1 19.75 16H4.25a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 4.25 3M6 16v5.5M18 16v5.5");
}

</style>
