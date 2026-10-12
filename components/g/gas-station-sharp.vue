<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0yzx1x0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gas-station-sharp" /></template>
<style>
.h0yzx1x0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3h18.5v4H2.75zM4 7v14.25M20 7v14.25m-17.25 0h18.5M7 10.75h4.5v10.5H7zM11.5 13H14v6h3v-6.5l-1.25-1.25");
}

</style>
