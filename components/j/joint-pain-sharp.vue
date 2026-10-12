<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yajzdxm1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joint-pain-sharp" /></template>
<style>
.yajzdxm1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.75h3.5V8.5l2 .4v1.85h-7.5V8.9l2-.4Zm0 18.5h3.5V15.5l2-.4v-1.85h-7.5v1.85l2 .4ZM3.5 9.75L6 11m-2.5 3.25L6 13m14.5-3.25L18 11m2.5 3.25L18 13");
}

</style>
