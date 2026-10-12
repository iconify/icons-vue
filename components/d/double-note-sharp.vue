<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo6uvdbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:double-note-sharp" /></template>
<style>
.bo6uvdbog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.9 19.86a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71Zm6.75-1.25a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71Zm6.75-1.25a2.5 1.8-20 1 0 4.7-1.71a2.5 1.8-20 1 0-4.7 1.71Zm-8.8.79V6m6.75 10.9V4.88m6.75 10.77V3.75M7.6 6l13.5-2.25");
}

</style>
