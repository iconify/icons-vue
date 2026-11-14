<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hdmrhmb2a"/><path class="i_ds90b7a"/><path class="nhlh76bpz"/><path class="ot42mbc9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-layer" /></template>
<style>
.hdmrhmb2a {
  d: path("M6 10.5h15.5l-2.5 5H7.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_ds90b7a {
  d: path("M8 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

.nhlh76bpz {
  d: path("M11 4.5c-5 0-8 2.5-8 7v7.75");
}

.ot42mbc9t {
  d: path("M2.5 19.25q1.75-1.25 3.5 0t3.5 0t3.5 0t3.5 0t3.5 0");
}

</style>
