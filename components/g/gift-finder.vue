<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf0dbqayp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-finder" /></template>
<style>
.cf0dbqayp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h12v4H3Zm1.5 4v5.5q0 3 3 3h3q1.111 0 1.811-.411m1.189-6.802V12M9 8v12.5M9 8C8 4.5 5 3.5 5 5.25S7.5 8 9 8Zm0 0c1-3.5 4-4.5 4-2.75S10.5 8 9 8Zm5.5 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25l2 2");
}

</style>
