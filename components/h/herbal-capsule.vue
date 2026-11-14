<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt1wbbb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herbal-capsule" /></template>
<style>
.yt1wbbb4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12h15.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 4.25 12Zm12.25 0c-2.5-3-1.5-7.5 4-8.5c1 4.5-1 7.5-4 8.5ZM12 12v7.5");
}

</style>
