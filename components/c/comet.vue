<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti02zx9jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comet" /></template>
<style>
.ti02zx9jp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm6-2.5L20 4M4.5 14.5l7-7m-2 12l7-7");
}

</style>
