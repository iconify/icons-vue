<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfbb8unuf"/><path class="zw0radpjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cream-tube" /></template>
<style>
.bfbb8unuf {
  d: path("m14.075 7.211l2.214 2.214a1.75 1.75 0 0 1 .218 2.208l-3.676 5.515a1.75 1.75 0 0 1-2.694.267l-4.052-4.052a1.75 1.75 0 0 1 .267-2.694l5.515-3.676a1.75 1.75 0 0 1 2.208.218");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zw0radpjy {
  d: path("m5.106 12.384l6.01 6.01a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0l-6.01-6.01a1.25 1.25 0 0 1 0-1.768a1.25 1.25 0 0 1 1.768 0M17.48 5.666l.354.354a1.5 1.5 0 0 1 0 2.121l-.354.354a1.5 1.5 0 0 1-2.121 0l-.354-.354a1.5 1.5 0 0 1 0-2.121l.354-.354a1.5 1.5 0 0 1 2.121 0M15.5 20q0-3.5 3-3.5t3 3.5Z");
}

</style>
