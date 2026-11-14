<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mglybebvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-jumping" /></template>
<style>
.mglybebvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 5.5c-4-2.75-8.75 0-8.25 4.75l-5-.75l2.75 2L7.5 15l2-4.75c3.75 2.75 8.5 0 8.25-4.75ZM3 19q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
