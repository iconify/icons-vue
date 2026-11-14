<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-glrxbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-drill-down" /></template>
<style>
.x-glrxbmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19V7h-19ZM12 9v4.5m-2.25-2.25L12 13.5l2.25-2.25M2.5 16h4.75v5.5H2.5Zm7.25 0h4.5v5.5h-4.5Zm7 0h4.75v5.5h-4.75Z");
}

</style>
