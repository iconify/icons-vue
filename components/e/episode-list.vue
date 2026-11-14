<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-i6-kbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:episode-list" /></template>
<style>
.z-i6-kbwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.75v4.5L6.5 5ZM10 5h11M2.5 9.75v4.5l4-2.25ZM10 12h11M2.5 16.75v4.5l4-2.25ZM10 19h11");
}

</style>
