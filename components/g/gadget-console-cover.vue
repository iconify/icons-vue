<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy7kr_bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gadget-console-cover" /></template>
<style>
.wy7kr_bwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7h13a3 3 0 0 1 3 3v4.5a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3V10a3 3 0 0 1 3-3Zm2 3.25v4m-2-2h4m6-1.25h.01M18 13.5h.01");
}

</style>
