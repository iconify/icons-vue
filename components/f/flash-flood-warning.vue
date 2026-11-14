<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqocbv67x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-flood-warning" /></template>
<style>
.zqocbv67x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16c3.5 0 5-3 6-6.5c1-4 3.5-6.5 7-6.5s6 2.5 6 5.5c0 2-2 3.25-3.75 3s-2.25-1.5-1.25-3M2.5 20H13m5-5.25v3.5M18 21h.01");
}

</style>
