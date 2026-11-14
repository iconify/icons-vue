<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bg3pnub4r"/><path class="pe3u3njpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garbage-patch" /></template>
<style>
.bg3pnub4r {
  d: path("M5 12.75V8.5Q5 7 6.5 6.25V3.5h2v2.75Q10 7 10 8.5v4.25ZM15.25 5.5h2A1.75 1.75 0 0 1 19 7.25V11a1.75 1.75 0 0 1-1.75 1.75h-2A1.75 1.75 0 0 1 13.5 11V7.25a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pe3u3njpu {
  d: path("m13.5 9l1.5 1l1.75-1.25l2.25 1M2.5 16.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-18 4q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
