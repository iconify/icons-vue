<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yegf0pbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drop-off-sharp" /></template>
<style>
.yegf0pbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.75h15.5v7.5H4.25zm0 2.5h15.5M12 2.75v8.5m-3.5-3.5l3.5 3.5l3.5-3.5");
}

</style>
