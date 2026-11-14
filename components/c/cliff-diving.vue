<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhnh7l27e"/><path class="m-4nu2iar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cliff-diving" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-4nu2iar {
  d: path("m17.5 14l2 2l2-2");
}

.vhnh7l27e {
  d: path("M2.5 19.5V4h5v4.5H11v11m-8.5 0h19m-8-13c4 0 6.25 3.5 6 9.5");
}

</style>
