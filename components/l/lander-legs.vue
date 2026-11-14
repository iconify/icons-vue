<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz1j2lb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lander-legs" /></template>
<style>
.uz1j2lb1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4.75h9l3 7h-15Zm0 7l-3 7.5m-2 0h4m10-7.5l3 7.5m-2 0h4m-9.5-7.5v7.5m-2 0h4");
}

</style>
