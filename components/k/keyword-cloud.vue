<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdzmszbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keyword-cloud" /></template>
<style>
.kdzmszbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.091 15.5H6.5c-2.25 0-4-1.75-4-4c0-2 1.5-3.75 3.5-4c.75-2.75 3.25-5 6.5-5c3.5 0 6.25 2.5 6.75 6c1.25.5 2.25 2 2.25 3.5c0 .317-.049.634-.142.94m-1.108 8.81h-2.379a1.5 1.5 0 0 1-1.06-.439l-1.75-1.75a1.5 1.5 0 0 1 0-2.122l2.378-2.378a1.5 1.5 0 0 1 2.122 0l1.75 1.75a1.5 1.5 0 0 1 .439 1.06v2.379a1.5 1.5 0 0 1-1.5 1.5m-1-2.5h.01");
}

</style>
