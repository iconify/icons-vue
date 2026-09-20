<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m5484o85t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:diamonds-four-thin" /></template>
<style>
.m5484o85t {
  fill: currentColor;
  d: path("M125.17 106.83a4 4 0 0 0 5.66 0l40-40a4 4 0 0 0 0-5.66l-40-40a4 4 0 0 0-5.66 0l-40 40a4 4 0 0 0 0 5.66ZM128 29.66L162.34 64L128 98.34L93.66 64Zm2.83 119.51a4 4 0 0 0-5.66 0l-40 40a4 4 0 0 0 0 5.66l40 40a4 4 0 0 0 5.66 0l40-40a4 4 0 0 0 0-5.66ZM128 226.34L93.66 192L128 157.66L162.34 192Zm106.83-101.17l-40-40a4 4 0 0 0-5.66 0l-40 40a4 4 0 0 0 0 5.66l40 40a4 4 0 0 0 5.66 0l40-40a4 4 0 0 0 0-5.66M192 162.34L157.66 128L192 93.66L226.34 128Zm-85.17-37.17l-40-40a4 4 0 0 0-5.66 0l-40 40a4 4 0 0 0 0 5.66l40 40a4 4 0 0 0 5.66 0l40-40a4 4 0 0 0 0-5.66M64 162.34L29.66 128L64 93.66L98.34 128Z");
}

</style>
