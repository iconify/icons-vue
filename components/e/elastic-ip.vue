<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuyb6_blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elastic-ip" /></template>
<style>
.yuyb6_blo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.6 14H2.5V2.5h19V14h-1.1m-2.3 0h-1.2M6.5 8.25h.01m4.49 0h7m-4.25 10.5h7.5m-5.5-2l-2 2l2 2m3.5-4l2 2l-2 2");
}

</style>
