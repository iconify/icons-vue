<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o8lr-jb8d"/><path class="j2omq6gic"/><path class="p36xabcxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:condo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2omq6gic {
  fill: currentColor;
  d: path("M13.5 5.25h3v2.5h-3Z");
}

.o8lr-jb8d {
  d: path("M7.125 2.5h9.75A2.625 2.625 0 0 1 19.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875V5.125A2.625 2.625 0 0 1 7.125 2.5m.375 4h3");
}

.p36xabcxn {
  d: path("M7.5 10.5h3m3 0h3m-9 4h3m3 0h3m-6 7v-3.25h3v3.25");
}

</style>
