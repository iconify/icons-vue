<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw675jbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crowd-barrier" /></template>
<style>
.zw675jbsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 6.75v-1.5A1.75 1.75 0 0 1 4.25 3.5m-.75 17L6 8.5l2.5 12m7 0l2.5-12l2.5 12M6 8.5l3-5m1.5 5l3-5m1.5 5l3-5");
}

</style>
