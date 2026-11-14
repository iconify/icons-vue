<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxksfjbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cells-under-microscope" /></template>
<style>
.lxksfjbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5v8h-5Zm2.5 8v3m-4 1h8M16 5c4 2 4.5 9 1 13.5M5.5 21h13M4 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm.75 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
