<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg49x9d4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-grid" /></template>
<style>
.cg49x9d4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5m-11-16.5v13m5.5-13v13m5.5-13v13M7 3.75h13.25M7 10.25h13.25");
}

</style>
