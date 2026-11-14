<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="proqndb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrows-in-cardinal" /></template>
<style>
.proqndb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12h.01M2.5 12h6m-3-3l3 3l-3 3m16-3h-6m3-3l-3 3l3 3M12 2.5v6m3-3l-3 3l-3-3m3 16v-6m3 3l-3-3l-3 3");
}

</style>
