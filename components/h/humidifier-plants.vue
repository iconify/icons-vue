<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whmt54ncq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidifier-plants" /></template>
<style>
.whmt54ncq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-8c0-2.5 1.5-3.5 3.25-3.5s3.25 1 3.25 3.5v8Zm10.5-6H21l-1 6h-5.5Zm3.75 0V9.5m0 1.5c0-3-1.75-4.5-4.25-4.5c0 3 1.75 4.5 4.25 4.5Zm0-1.5c0-3 1.75-4.5 4.25-4.5c0 3-1.75 4.5-4.25 4.5Zm-11-3h.01M9.5 5h.01M6.5 3.25h.01");
}

</style>
