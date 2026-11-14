<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mevm-bbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrow-merge-down" /></template>
<style>
.mevm-bbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5v4c0 3.5 5 3.5 5 7m5-11v4c0 3.5-5 3.5-5 7m0 0v6M8.5 17l3.5 3.5l3.5-3.5");
}

</style>
