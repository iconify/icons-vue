<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh6zk2_0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heavy-rain-sharp" /></template>
<style>
.jh6zk2_0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.86 13.02a3.24 3.24 0 0 1-.45-6.45a4.66 4.66 0 0 1 8.63-1.12a3.64 3.64 0 0 1-.49 7.57Zm-.36 3.23l-1.5 5m5.25-5l-1.5 5m5.25-5l-1.5 5m5.25-5l-1.5 5");
}

</style>
