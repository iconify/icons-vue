<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad417fcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bridge-beam" /></template>
<style>
.ad417fcvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h19v3h-19ZM6 8h3.5v6H6Zm8.5 0H18v6h-3.5ZM3 18q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
