<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b80o2bbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corner-flag" /></template>
<style>
.b80o2bbjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V3.5m1.996.698l3.959 1.386a1.5 1.5 0 0 1 0 2.832L5.996 9.802A1.5 1.5 0 0 1 4 8.386V5.614a1.5 1.5 0 0 1 1.996-1.416M4 21h17M4 16a5 5 0 0 1 5 5");
}

</style>
