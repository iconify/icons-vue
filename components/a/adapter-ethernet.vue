<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0157kvlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adapter-ethernet" /></template>
<style>
.r0157kvlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h15v11h-15Zm3.5 11h8L14.5 18h-5Zm4 3.5v3.5m-3.5-18V7M12 3.5V7m3.5-3.5V7");
}

</style>
