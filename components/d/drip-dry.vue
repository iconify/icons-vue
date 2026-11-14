<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ql4dbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drip-dry" /></template>
<style>
.t-ql4dbex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5L3 6.5l1.75 4L7 9.5V17h10V9.5l2.25 1l1.75-4l-5.5-3c-1 1.75-6 1.75-7 0Zm.5 17h.01M12 21h.01m2.99-.5h.01");
}

</style>
