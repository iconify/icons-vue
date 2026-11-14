<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqvb0nboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:low-beam" /></template>
<style>
.pqvb0nboy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 6c4.25 0 7 2.5 7 6s-2.75 6-7 6Zm-10 1.5l6 2m-6 2.5l6 2m-6 2.5l6 2");
}

</style>
