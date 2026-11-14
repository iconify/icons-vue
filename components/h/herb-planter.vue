<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atn5qqbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herb-planter" /></template>
<style>
.atn5qqbdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5h17v3h-17Zm1.5 3h14L18 21H6Zm3-3v-4c0-3-2-5-4.5-5c0 3 2 5 4.5 5m8 4v-4c0-3 2-5 4.5-5c0 3-2 5-4.5 5");
}

</style>
