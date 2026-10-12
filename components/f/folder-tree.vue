<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szs117bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-tree" /></template>
<style>
.szs117bsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4A1.25 1.25 0 0 1 4 2.75h1.75l1 1H9A1.25 1.25 0 0 1 10.25 5v1.5A1.25 1.25 0 0 1 9 7.75H4A1.25 1.25 0 0 1 2.75 6.5Zm11 6.25A1.25 1.25 0 0 1 15 9h1.75l1 1H20a1.25 1.25 0 0 1 1.25 1.25V12A1.25 1.25 0 0 1 20 13.25h-5A1.25 1.25 0 0 1 13.75 12Zm0 7.5A1.25 1.25 0 0 1 15 16.5h1.75l1 1H20a1.25 1.25 0 0 1 1.25 1.25v.75A1.25 1.25 0 0 1 20 20.75h-5a1.25 1.25 0 0 1-1.25-1.25Zm-7.25-7.5V19h4.75M6.5 11.75h4.75");
}

</style>
