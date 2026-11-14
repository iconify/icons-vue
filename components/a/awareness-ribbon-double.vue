<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw80vns5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:awareness-ribbon-double" /></template>
<style>
.gw80vns5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5L13.5 9c1.5-2 1-6.5-2.5-6.5S7 7 8.5 9l4.577 6.193M18 15v6m-3-3h6");
}

</style>
