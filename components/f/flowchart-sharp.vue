<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc-arubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flowchart-sharp" /></template>
<style>
.bc-arubtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.75h9V6.5H4zM8.5 6.5v2.75m0 5.5v2.75m2.75-5.5h4.5M9.03 9.78l1.69 1.69l.53.53l-.53.53l-1.69 1.69l-.53.53l-.53-.53l-1.69-1.69l-.53-.53l.53-.53l1.69-1.69l.53-.53zM4 17.5h9v3.75H4zm11.75-7.75h5.5v4.5h-5.5z");
}

</style>
