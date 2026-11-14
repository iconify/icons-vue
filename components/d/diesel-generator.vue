<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j78rs4buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diesel-generator" /></template>
<style>
.j78rs4buh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 19.5H2.5V9h16v2.5M6.5 9V3H10M6 13h5m-5 3h3m10.25-1.25L16 18.25h4l-3.25 3.5");
}

</style>
