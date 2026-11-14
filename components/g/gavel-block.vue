<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynndqib1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gavel-block" /></template>
<style>
.ynndqib1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.873 10.195l7.072-7.072l3.182 3.182l-7.072 7.072ZM12.5 9.75l7.5 7.5m-16.5.25h11V21h-11Z");
}

</style>
