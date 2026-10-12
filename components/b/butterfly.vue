<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dusarn6ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:butterfly" /></template>
<style>
.dusarn6ol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 11C9.75 7.25 7.25 4.25 5 4.25c-1.25 0-2.25.75-2.25 2.25c0 2.75 2 4.5 5.5 4.5Zm2 0c1.25-3.75 3.75-6.75 6-6.75c1.25 0 2.25.75 2.25 2.25c0 2.75-2 4.5-5.5 4.5Zm-1 2c-3-.25-6.5.75-6.5 3.5c0 1.75 1.25 3 2.75 3c2 0 3-3 3.75-6.5m0 0c3-.25 6.5.75 6.5 3.5c0 1.75-1.25 3-2.75 3c-2 0-3-3-3.75-6.5m0-5.5V13m0-5.5l-1.5-3m1.5 3l1.5-3");
}

</style>
