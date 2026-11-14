<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5fo53lwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:line-status" /></template>
<style>
.l5fo53lwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h8.5M3 12.5h8.5M3 19h8.5m3-13h.01m-.01 6.5h.01M14.5 19h.01m2.74-13l1.5 1.5l2.75-3.25");
}

</style>
