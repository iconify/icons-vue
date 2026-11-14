<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecv-ggphd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gauze-bite" /></template>
<style>
.ecv-ggphd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 18H3V3h15v9.3M3 11l8-8m5.5 12c-1.25 0-1.75 1-1.75 2.25s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75S20.25 15 19 15c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5Z");
}

</style>
