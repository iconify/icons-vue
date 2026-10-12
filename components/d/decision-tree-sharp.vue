<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo_eigbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decision-tree-sharp" /></template>
<style>
.eo_eigbli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.71 3.46l2.08 2.08l.71.71l-.71.71l-2.08 2.08l-.71.71l-.71-.71l-2.08-2.08l-.71-.71l.71-.71l2.08-2.08l.71-.71zM8.5 6.25H6v8m9.5-8H18v8m-15.25 0h6.5v6.5h-6.5zm12 0h6.5v6.5h-6.5z");
}

</style>
