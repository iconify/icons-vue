<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysp209b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-butterfly" /></template>
<style>
.ysp209b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14a1.5 1.5 0 1 1-1.25 2.25a1.5 1.5 0 1 1-2.5 0A1.5 1.5 0 1 1 5.5 14a1.5 1.5 0 1 1 1.25-2.25a1.5 1.5 0 1 1 2.5 0A1.5 1.5 0 1 1 10.5 14ZM8 18.5v3m9.5-15c-3-5.5-5.25-2.5-3 0c-2.25 2.5.5 5 3 1.5c2.5 3.5 5.25 1 3-1.5c2.25-2.5 0-5.5-3 0ZM8 14h.01m9.49-9.5v6");
}

</style>
