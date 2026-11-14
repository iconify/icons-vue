<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6v0asvmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-skeleton" /></template>
<style>
.j6v0asvmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 7.5c3.5 0 5 2.5 5 4.5s-1.5 4.5-5 4.5ZM4.5 12h12m-9-3v6m3-6.5v7m3-7.5v8m-11-7.5l2 3.5l-2 3.5");
}

</style>
