<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s13a5qbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-on-ice" /></template>
<style>
.s13a5qbxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9c2.5-4 6-5.5 9.5-5.5S18 6 18 9s-2 5.5-5.5 5.5S5.5 13 3 9Zm15 0l3.5-3.5v7ZM7.5 8h.01M4 17.5h4V21H4Zm6 0h4V21h-4Zm6 0h4V21h-4Z");
}

</style>
