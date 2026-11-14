<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcylo5bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:influencer-list" /></template>
<style>
.zcylo5bia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 19c0-3.5 2-5 4.5-5s4.5 1.5 4.5 5m3-11.5h7m-7 4.5h7m-7 4.5H19");
}

</style>
