<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe4rd2byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joint-pain" /></template>
<style>
.fe4rd2byy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.75h3.5V8.5c1.25.25 2 1.1 2 2.25h-7.5c0-1.15.75-2 2-2.25Zm0 18.5h3.5V15.5c1.25-.25 2-1.1 2-2.25h-7.5c0 1.15.75 2 2 2.25ZM3.5 9.75L6 11m-2.5 3.25L6 13m14.5-3.25L18 11m2.5 3.25L18 13");
}

</style>
