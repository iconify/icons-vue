<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hshapox1u"/><path class="b2_nq4b9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-flip-screen" /></template>
<style>
.b2_nq4b9e {
  d: path("m16.487 7.641l2.5-.909A1.5 1.5 0 0 1 21 8.142v8.716a1.5 1.5 0 0 1-2.013 1.41l-2.5-.909a1.5 1.5 0 0 1-.987-1.41V9.051a1.5 1.5 0 0 1 .987-1.41M7.25 9.5h3.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 10.75 15h-3.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 7.25 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hshapox1u {
  d: path("M2.5 8.5a2 2 0 0 1 2-2h2l1.5-2h3l1.5 2h3V18h-11a2 2 0 0 1-2-2Z");
}

</style>
