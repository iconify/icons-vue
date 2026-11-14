<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dalx-lh_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:buy-two-get-one" /></template>
<style>
.dalx-lh_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h9v7.5h-9Zm10 0h9v7.5h-9Zm-5-7.5h9V14h-9Zm4.5 0V14m0-7.5c0-3.25-3-4-3-2c0 1.25 2 2 3 2s3-.75 3-2c0-2-3-1.25-3 2Z");
}

</style>
