<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqx_dlbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:awareness-ribbon-loop" /></template>
<style>
.sqx_dlbze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 21.5L14.5 13c1.25-2 1.5-3.75 1.5-5.5C16 5 14.25 3 12 3S8 5 8 7.5c0 1.75.25 3.5 1.5 5.5l5.75 8.5");
}

</style>
