<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvata750o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-night" /></template>
<style>
.wvata750o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 4a7 7 0 1 0 3.25 7.75A5.5 5.5 0 0 1 13 4Zm1.288 15.134l4.596-4.596l2.828 2.828l-4.596 4.596Zm2.298-2.298l2.828 2.828");
}

</style>
