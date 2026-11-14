<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grj3dxbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beat-grid" /></template>
<style>
.grj3dxbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v18H3Zm4.5 0v18M12 3v18m4.5-18v18M3 7.5h18M3 12h18M3 16.5h18M9.75 5.25h.01m8.99 4.5h.01m-13.51 4.5h.01m8.99 4.5h.01");
}

</style>
