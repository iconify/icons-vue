<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6gefabmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commuter-benefit" /></template>
<style>
.n6gefabmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h11A1.5 1.5 0 0 1 19 4.5V16a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 16V4.5A1.5 1.5 0 0 1 6.5 3ZM5 10h14m-9-4h4m-5.5 7.75h.01m6.99 0h.01M7.5 17.5L5 21m11.5-3.5L19 21");
}

</style>
