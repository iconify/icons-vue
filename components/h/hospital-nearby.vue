<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkfecxb8k"/><path class="vuom80bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-nearby" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkfecxb8k {
  d: path("M3 21.5V9h5V3.5h8V9h5v12.5ZM12 9v5.5m-2.75-2.75h5.5");
}

.vuom80bix {
  d: path("M10 21.5v-4h4v4M5.5 13h.01m-.01 4h.01m12.99-4h.01m-.01 4h.01");
}

</style>
