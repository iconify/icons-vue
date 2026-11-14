<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4u42fbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-oil" /></template>
<style>
.m4u42fbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11h10v10.5h-10ZM6 8h5v3H6Zm1 0V4.5a1.5 1.5 0 0 1 3 0V8m9 4s-2.5 3.5-2.5 5.5a2.5 2.5 0 0 0 5 0c0-2-2.5-5.5-2.5-5.5Z");
}

</style>
