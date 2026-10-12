<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euiyvkbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contour-integral" /></template>
<style>
.euiyvkbdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 4.5c-.5-.75-1.25-1.25-2.25-1.25c-1.75 0-2.75 1.25-3 3l-1.5 11.5c-.25 1.75-1.25 3-3 3c-1 0-1.75-.5-2.25-1.25");
}

</style>
