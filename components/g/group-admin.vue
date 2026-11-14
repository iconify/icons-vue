<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3v4lrtmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-admin" /></template>
<style>
.k3v4lrtmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5V3l2.5 2.25L12 2.5l2.5 2.75L17 3v4.5ZM5 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm9 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 21.5c0-2 2-3.25 4.5-3.25S12 19.5 12 21.5m0 0c0-2 2-3.25 4.5-3.25S21 19.5 21 21.5");
}

</style>
