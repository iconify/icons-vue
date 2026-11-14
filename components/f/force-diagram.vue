<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gofw39mza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:force-diagram" /></template>
<style>
.gofw39mza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.688 8.5h2.625a2.19 2.19 0 0 1 2.187 2.188v2.625a2.19 2.19 0 0 1-2.187 2.187h-2.625A2.19 2.19 0 0 1 8.5 13.313v-2.625A2.19 2.19 0 0 1 10.688 8.5M12 8.5V3m-2 2l2-2l2 2m1.5 7H21m-2-2l2 2l-2 2m-7 1.5V21m-2-2l2 2l2-2m-5.5-7H3m2-2l-2 2l2 2");
}

</style>
