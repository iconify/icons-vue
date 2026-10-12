<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4s6_yh4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inpaint-brush-sharp" /></template>
<style>
.w4s6_yh4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.17 3.17l.66.66l.42.42l-.4.45l-5.95 6.6l-.4.45l-.42-.42l-1.41-1.41l-.42-.42l.45-.4l6.6-5.95l.45-.4zm-9.67 8.08l2.25 2.25c-.4 2.9-2.4 4.6-6 4.4c.6-3.4 1.6-6.1 3.75-6.65Zm-7.75 3v1.5m0 3.25v2.25H5m3.25 0h1.5");
}

</style>
