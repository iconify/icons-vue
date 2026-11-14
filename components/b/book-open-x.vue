<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caod-4slk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-open-x" /></template>
<style>
.caod-4slk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 13.076V4.75c-2.5-.5-5.75 0-8 1.5c-2.25-1.5-5.5-2-8.5-1.5V18.5c3-.5 6.25 0 8.5 1.5a9.4 9.4 0 0 1 2.143-1.044M11 6.25V20m4.5-4.5l5 5m0-5l-5 5");
}

</style>
