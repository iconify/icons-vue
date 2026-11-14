<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6m9kdlpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fort-bastion" /></template>
<style>
.m6m9kdlpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V9h3v2.5h3V9h3v2.5h3V9h3l3.5 3.5V21ZM4.5 9V2.5m0 0L9 4L4.5 5.5Z");
}

</style>
