<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haladobdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-flag-sharp" /></template>
<style>
.haladobdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.75v16.5M8.75 3h12.5v7.5H8.75zm-6 18.25C5.25 19.5 8.25 19 12 19s6.75.5 9.25 2.25");
}

</style>
