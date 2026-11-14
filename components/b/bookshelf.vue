<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwz8-syng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookshelf" /></template>
<style>
.iwz8-syng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21h18M3 11.5h18M4.5 4h3v7.5h-3ZM9 5.5h3v6H9ZM13.5 4h3v7.5h-3ZM5 14h3v7H5Zm5 1.5h3V21h-3Zm5.5 5.5l1.5-7l3 .75L18.5 21Z");
}

</style>
