<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mza24j0an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:distribute-center-horizontal" /></template>
<style>
.mza24j0an {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.688 6h1.625A2.19 2.19 0 0 1 9.5 8.188v7.625A2.19 2.19 0 0 1 7.313 18H5.688A2.19 2.19 0 0 1 3.5 15.813V8.188A2.19 2.19 0 0 1 5.688 6m10.5 2.5h2.125a2.19 2.19 0 0 1 2.187 2.188v2.625a2.19 2.19 0 0 1-2.187 2.187h-2.125A2.19 2.19 0 0 1 14 13.313v-2.625A2.19 2.19 0 0 1 16.188 8.5M6.5 2.5V6m0 12v3.5m10.75-19v6m0 7v6");
}

</style>
