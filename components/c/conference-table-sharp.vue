<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9dnn-bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conference-table-sharp" /></template>
<style>
.g9dnn-bcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.75h6.5v16.5h-6.5zm-6 2.75h3V10h-3zm0 7.5h3v3.5h-3zm15.5-7.5h3V10h-3zm0 7.5h3v3.5h-3z");
}

</style>
