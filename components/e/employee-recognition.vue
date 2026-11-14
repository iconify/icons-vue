<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tdo0-wb3y"/><path class="i--coi88a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employee-recognition" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i--coi88a {
  fill: currentColor;
  d: path("m12.588 7.066l.24.639a1.5 1.5 0 0 0 1.337.971l.682.031a.628.628 0 0 1 .363 1.118l-.534.426a1.5 1.5 0 0 0-.511 1.571l.182.658a.628.628 0 0 1-.951.691l-.57-.376a1.5 1.5 0 0 0-1.652 0l-.57.376a.628.628 0 0 1-.951-.691l.182-.658a1.5 1.5 0 0 0-.511-1.571l-.534-.426a.628.628 0 0 1 .363-1.118l.682-.031a1.5 1.5 0 0 0 1.337-.971l.24-.639a.628.628 0 0 1 1.176 0");
}

.tdo0-wb3y {
  d: path("M2.5 5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v10a2.5 2.5 0 0 1-2.5 2.5h-8L6.5 21v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

</style>
