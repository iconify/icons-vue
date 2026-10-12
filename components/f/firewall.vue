<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vv12bjbqw"/><path class="xnxqm7wyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:firewall" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vv12bjbqw {
  width: 18.5px;
  height: 6.25px;
  x: 2.75px;
  y: 15px;
  rx: 2px;
}

.xnxqm7wyu {
  d: path("M2.75 18.25h18.5M8.5 15v3.25m7-3.25v3.25m-3.5 0v3m0-18.5c.45 1.75 1.8 2.75 2.6 3.9c.45.7.65 1.4.65 2.1a3.25 3.25 0 0 1-6.5 0c0-.95.4-1.85 1.1-2.6c.25.85.75 1.4 1.35 1.5c-.05-1.7.15-3.25.8-4.9");
}

</style>
