<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwlv88n8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disassembly" /></template>
<style>
.qwlv88n8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9.5h-4A2.5 2.5 0 0 0 3 12v7a2.5 2.5 0 0 0 2.5 2.5h4Zm5 0h4A2.5 2.5 0 0 1 21 12v7a2.5 2.5 0 0 1-2.5 2.5h-4Zm-5-5h-6m2-2l-2 2l2 2m9-2h6m-2-2l2 2l-2 2");
}

</style>
