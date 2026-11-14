<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czfiy4dxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hammer" /></template>
<style>
.czfiy4dxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5A1.5 1.5 0 0 1 5 3h9c3 0 5.5 1.5 6.5 4.5c-2-1-4-1-6.5 0v1H5A1.5 1.5 0 0 1 3.5 7Zm5.5 4h4v13H9Z");
}

</style>
