<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oirsfey3i"/><path class="u7f-qkb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caravan-camel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oirsfey3i {
  d: path("m20.37 9.73l-2.11-2.58q-.63-.77-1.59-1.04l-.71-.21q-.96-.27-1.81.26l-1.3.81q-.85.53-1.56 1.24l-.83.83q-.71.71-1.12-.2l-1.05-2.3q-.41-.91-1.12-1.62l-.08-.08q-.71-.71-1.7-.59l-1.02.13q-.99.12-1.18.87t.7 1.2l.47.23q.89.45 1.21 1.4l.49 1.47q.32.95.92 1.75l1.05 1.4q.6.8 1.6.8h8.87q1 0 1.45-.89l.6-1.22q.45-.89-.18-1.66m-1.99 3.77v6.38m-2.63-6.38v6.38m-4.87-6.38v6.38M8.63 13.5v6.38");
}

.u7f-qkb6j {
  d: path("M17.25 13.5V9.75h-4.5v3.75");
}

</style>
