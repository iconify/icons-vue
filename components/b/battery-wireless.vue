<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4eciws9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-wireless" /></template>
<style>
.r4eciws9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H19v9H2.5Zm19 3v3M6.25 5.5a6.5 6.5 0 0 1 9 0m-7 2.5a3.5 3.5 0 0 1 5 0");
}

</style>
