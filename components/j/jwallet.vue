<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0eoqfujt"/><path class="atn1f4bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jwallet" /></template>
<style>
.atn1f4bwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.023 34.45A13.1 13.1 0 0 0 24 37.148c7.26 0 13.147-5.886 13.147-13.147V6.988");
}

.c0eoqfujt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.402 12.876A21.4 21.4 0 0 1 45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5c2.473 0 4.85.418 7.06 1.186");
}

</style>
