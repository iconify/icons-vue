<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt-23jb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-sign" /></template>
<style>
.gt-23jb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 11V6a3.5 3.5 0 0 1 3.5-3.5m.5 12v7m10-7v7m-7.75-16v6m5.5-6v6m-5.5-3h5.5");
}

</style>
