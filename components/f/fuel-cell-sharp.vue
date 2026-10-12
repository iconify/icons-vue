<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubo8obywh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-cell-sharp" /></template>
<style>
.ubo8obywh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7h16v14.25H4zm4 0V4.25M16 7V4.25m-9.25 0h2.5m5.5 0h2.5M8.5 10.5v7m3.5-7v7m3.5-7v7");
}

</style>
