<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b15dyxbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bass-guitar-sharp" /></template>
<style>
.b15dyxbum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.81 12.76c-.91-1.22-2.43-1.22-3.19-.16c-1.28.25-3.8 2.89-.76 5.93s5.47 1.52 6.08 0c1.37-.76 1.67-2.28.3-3.34Zm1.22 1.21l6.38-6.38m3.15-3.55l.4.4l.71.71l-.71.71l-1.92 1.93l-.71.71l-.71-.71l-.41-.41l-.71-.71l.71-.71l1.93-1.92l.71-.71zm-1.54.11l-.91-.91m-.76 2.58l-.91-.91m4.41 1.07l.91.91m-2.58.76l.91.91M6.53 15.04l2.43 2.43");
}

</style>
