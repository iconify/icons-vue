<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ha-4xqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-sweater" /></template>
<style>
.a-ha-4xqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5L2.5 15L5 16.5L7.5 10v11h9V10l2.5 6.5l2.5-1.5l-6-10.5Zm1 0V2.75h5V4.5m-7 13.75h9");
}

</style>
