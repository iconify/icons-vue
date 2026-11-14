<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3d69kbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breast-pump" /></template>
<style>
.q3d69kbeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11.5h8v10H6ZM7 9h6v2.5H7Zm1.5 0q-2.25-2.25-6-2.25V2.5c3.75 0 7.25 2.25 9.25 6.5M14 14q4.5 0 6 3v4.5");
}

</style>
