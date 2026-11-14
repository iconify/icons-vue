<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnx5s3t4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifeguard-whistle" /></template>
<style>
.rnx5s3t4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h11.5A5.5 5.5 0 1 1 9 14.5V13H3Zm11.5 5.5h.01M4.5 9C3.5 5.5 6 3 9 3.5");
}

</style>
