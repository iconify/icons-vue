<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdnof8b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handheld-shot" /></template>
<style>
.fdnof8b6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6h8v8h-8Zm8 2.5l5-2v7l-5-2ZM11 14v4.5h3.5V14m-12-6h3.25M2.5 12h3.25");
}

</style>
