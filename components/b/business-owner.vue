<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mque21bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-owner" /></template>
<style>
.mque21bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.753 0 1.475.071 2.153.205M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 10.25l1-2.75H21l1 2.75Zm1 0v4.25H21v-4.25");
}

</style>
