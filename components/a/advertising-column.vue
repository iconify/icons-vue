<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-0of3rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:advertising-column" /></template>
<style>
.g6-0of3rc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7c0-4.5 13-4.5 13 0Zm1 0v14.5M17.5 7v14.5m-13 0h15M9.25 10h5.5v8.5h-5.5Z");
}

</style>
