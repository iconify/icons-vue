<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="refomsbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dibber-tool" /></template>
<style>
.refomsbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5h9A1.5 1.5 0 0 1 18 5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 5a1.5 1.5 0 0 1 1.5-1.5m2.5 3V12l2 8l2-8V6.5M2.5 17h6m7 0h6");
}

</style>
