<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o800htg0l"/><path class="gljqkccrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arm" /></template>
<style>
.gljqkccrr {
  d: path("M3.5 7.5c1.5.75 3.5.75 5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o800htg0l {
  d: path("M3 5.5c0-1.75 1.25-3 3-3s3 1.25 3 3v7c0 .6.4 1 1 1h4.5L16 11c.5-.75 1.75-.5 1.5.5l-.25 1.5h2.25c1.1 0 2 .9 2 2.25s-.9 2.25-2 2.25l-5 1L6 19c-1.75 0-3-1.25-3-3Z");
}

</style>
