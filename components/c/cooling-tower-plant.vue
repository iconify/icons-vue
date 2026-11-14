<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngk0w_88e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cooling-tower-plant" /></template>
<style>
.ngk0w_88e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21q3-7 1-12h6q-2 5 1 12Zm11 0q3-7 1-12h6q-2 5 1 12ZM4 6.25a1.75 1.75 0 0 1 2.5-2a1.75 1.75 0 0 1 2.5 2m6 0a1.75 1.75 0 0 1 2.5-2a1.75 1.75 0 0 1 2.5 2");
}

</style>
