<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ysni955vn"/><path class="umt3pxcmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hearts-two" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umt3pxcmk {
  d: path("M15 19.5s-5.5-3.5-5.5-7c0-1.75 1.25-3 2.75-3c1.25 0 2.25.75 2.75 1.5c.5-.75 1.5-1.5 2.75-1.5c1.5 0 2.75 1.25 2.75 3c0 3.5-5.5 7-5.5 7");
}

.ysni955vn {
  d: path("M6.68 12.71C5.178 11.366 3.5 9.433 3.5 7.5c0-1.75 1.25-3 2.75-3C7.5 4.5 8.5 5.25 9 6c.5-.75 1.5-1.5 2.75-1.5c1.383 0 2.553 1.062 2.728 2.6");
}

</style>
