<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdc-o8kct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kindergarten" /></template>
<style>
.pdc-o8kct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5H11v8H3.5Zm9.5 0h7.5v8H13ZM6 10l6-6.5l6 6.5Zm1.25 6.5h.01m9.49 0h.01");
}

</style>
