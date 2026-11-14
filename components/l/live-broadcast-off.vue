<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqmi7tbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-broadcast-off" /></template>
<style>
.zqmi7tbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 3.5H16v8.6m-4.4 3.4H2.5V6.4M16 7.5l5.5-3v10l-5.5-3m-4.5-4h.01m-8.01-4l17 17");
}

</style>
