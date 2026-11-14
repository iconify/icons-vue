<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzdyw3boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breaking-banner" /></template>
<style>
.tzdyw3boc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8H14l2.5-1.5l1.75 3l3-.25L19.5 12l1.75 2.75l-3-.25l-1.75 3L14 16H4.5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Zm1 4H11");
}

</style>
