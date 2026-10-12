<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1q9j-asq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bar-chart-negative-sharp" /></template>
<style>
.n1q9j-asq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h18.5m-17-6.75h3.5v4.5h-3.5zm6 9h3.5v7h-3.5zm6-11.5h3.5v7h-3.5z");
}

</style>
