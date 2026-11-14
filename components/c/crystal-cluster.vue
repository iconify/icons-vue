<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmeih7bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crystal-cluster" /></template>
<style>
.cmeih7bvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h18m-12 0V7l3-4l3 4v13.5ZM9 13l-2.5-2.5l-2 2.5v7.5m10.5-10L17.5 8l2 2.5v10");
}

</style>
