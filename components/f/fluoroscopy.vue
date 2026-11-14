<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xealpkbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fluoroscopy" /></template>
<style>
.xealpkbtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.25H8.5c-3.25 0-6 2.5-6 6s2.75 6 6 6h3.715M6 15v6.5m-3 0h6.5M13 2v2.5m2 10l6.5 3.5l-6.5 3.5Z");
}

</style>
