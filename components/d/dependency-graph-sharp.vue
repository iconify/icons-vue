<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qupo18rcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dependency-graph-sharp" /></template>
<style>
.qupo18rcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75h7v4.5h-7zm-5.75 7h7v4.5h-7zm11.5 0h7v4.5h-7zm-5.75 7h7v4.5h-7zm1.5-9.5l-2 2.5m6-2.5l2 2.5m-8 4.5l2 2.5m6-2.5l-2 2.5");
}

</style>
