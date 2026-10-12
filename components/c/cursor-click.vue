<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5uimcyem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-click" /></template>
<style>
.r5uimcyem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.66 8.96l8.93 3.58q1.16.46-.03.84l-3.12.99q-1.19.38-1.59 1.57l-.95 2.87q-.4 1.19-.81.01L8.91 9.68q-.41-1.18.75-.72m-4.7 3.08a5 5 0 0 1 7.08-7.08");
}

</style>
