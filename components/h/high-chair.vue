<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmxs7uboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:high-chair" /></template>
<style>
.cmxs7uboj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 5h4.75A2.625 2.625 0 0 1 17 7.625v.75A2.625 2.625 0 0 1 14.375 11h-4.75A2.625 2.625 0 0 1 7 8.375v-.75A2.625 2.625 0 0 1 9.625 5M7 11v9.5M17 11v9.5m-13-6h16m-15 6h14");
}

</style>
