<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kue4bx_ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canopic-jar" /></template>
<style>
.kue4bx_ze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9c-3.5 2-3.5 9 0 12h10c3.5-3 3.5-10 0-12Zm0 0c0-3.5 2.25-4.5 5-4.5s5 1 5 4.5m-5-6.5v2");
}

</style>
