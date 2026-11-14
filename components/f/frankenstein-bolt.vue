<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="te446mb3h"/><path class="o-naylwhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frankenstein-bolt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-naylwhk {
  d: path("M5.5 7.5L8.75 9L12 7.5L15.25 9l3.25-1.5m-9 5.25h.01m4.99 0h.01m-5.01 4h5");
}

.te446mb3h {
  d: path("M9 3h6a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 17V6.5A3.5 3.5 0 0 1 9 3m-6.5 9.5h3v3h-3Zm16 0h3v3h-3Z");
}

</style>
