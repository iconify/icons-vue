<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw759xbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flashlight-sharp" /></template>
<style>
.iw759xbqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25h5.5l.74-.67l1.27-1.16l.74-.67h4v10.5h-4l-.74-.67l-1.27-1.16l-.74-.67h-6.5v-5.5zM5.25 12h2.5M18 8.25l3.25-1.5m-3 5.25h3M18 15.75l3.25 1.5");
}

</style>
