<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td3vzbw4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engine" /></template>
<style>
.td3vzbw4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8h9.5l2 2.5H21V16h-2.5L16 18.5H9.5L7 16H4.5v-5.5H7Zm2.5-3h5M12 5v3m-9.5 3v4.5");
}

</style>
