<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wh0z9ksir"/><path class="hrp3jk4pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:live-stream" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrp3jk4pe {
  d: path("m10.76 12.81l3.48 2.13q.51.31 0 .62l-3.48 2.13q-.51.31-.51-.29v-4.3q0-.6.51-.29M9 7.75a4.25 4.25 0 0 1 6 0M6.25 5.5a8.25 8.25 0 0 1 11.5 0");
}

.wh0z9ksir {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  rx: 2.5px;
}

</style>
