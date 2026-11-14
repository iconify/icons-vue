<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cefl24cxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aspergillum" /></template>
<style>
.cefl24cxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.914 3.757l2.829 2.829a1 1 0 0 1 0 1.414L15.5 12.243a1 1 0 0 1-1.414 0l-2.829-2.829a1 1 0 0 1 0-1.414L15.5 3.757a1 1 0 0 1 1.414 0ZM12.75 10.75L4.5 19M15 17h.01m3.49-.5h.01m1.99-3h.01");
}

</style>
