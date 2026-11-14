<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrheip62f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-stick-tape" /></template>
<style>
.lrheip62f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 3.5L13 16v2.25a2.25 2.25 0 0 1-2.25 2.25h-5a2.25 2.25 0 0 1 0-4.5H13m-5.25 0v4.5M10.5 16v4.5");
}

</style>
