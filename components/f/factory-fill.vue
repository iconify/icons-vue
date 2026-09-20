<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tblfglbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:factory-fill" /></template>
<style>
.tblfglbbb {
  fill: currentColor;
  d: path("M232 208h-8v-72.98a1 1 0 0 0 0-.15L209 29.74A16.08 16.08 0 0 0 193.06 16h-18.12a16.08 16.08 0 0 0-15.84 13.74l-11.56 80.91L108.8 81.6A8 8 0 0 0 96 88v32L44.8 81.6A8 8 0 0 0 32 88v120h-8a8 8 0 0 0 0 16h208a8 8 0 0 0 0-16m-124-24H80a8 8 0 0 1 0-16h28a8 8 0 0 1 0 16m68 0h-28a8 8 0 0 1 0-16h28a8 8 0 0 1 0 16m-5.33-56l-8.53-6.4l12.8-89.6h18.12l13.72 96Z");
}

</style>
