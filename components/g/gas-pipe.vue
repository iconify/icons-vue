<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i51vfybzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-pipe" /></template>
<style>
.i51vfybzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5H10a2 2 0 0 0 2-2v-6h4v6a6 6 0 0 1-6 6H2.5Zm0-1v6m8.5-13h6m.25 11c.5 2 4.25 2.5 4.25 5a3.5 3.5 0 0 1-7 0c0-1.5.75-2.25 1.5-2.75c0 1 .5 1.5 1 1.75c.5-1.5.25-2.75.25-4Z");
}

</style>
