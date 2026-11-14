<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gls31kgsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grout-brush" /></template>
<style>
.gls31kgsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12v4H6Zm3 4v3.25m3-3.25v3.25m3-3.25v3.25M3.5 13h17v8.5h-17Zm8.5 0v8.5m-8.5-4.25h17");
}

</style>
