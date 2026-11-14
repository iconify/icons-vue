<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa1dl0f3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doorbell-chime" /></template>
<style>
.aa1dl0f3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.5a6 6 0 0 1 12 0v4l1.5 2.25c.35.5.1 1.25-.5 1.25H5c-.6 0-.85-.75-.5-1.25L6 14.5Zm6-8v2M10 21h4");
}

</style>
