<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qihiw3b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-takeoff" /></template>
<style>
.qihiw3b-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h6m-3 0V8H9m0-2.25h6v5H9Zm6.5-2.25h6m-3 0V8H15m-4.5 2.75L9 13.5m4.5-2.75L15 13.5m3 7.5v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
