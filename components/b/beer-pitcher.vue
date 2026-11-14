<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a774cdb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beer-pitcher" /></template>
<style>
.a774cdb_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h12.5v16A1.5 1.5 0 0 1 15 21H7a1.5 1.5 0 0 1-1.5-1.5V6Zm12.5 3h2A1.5 1.5 0 0 1 20 8v6.5a1.5 1.5 0 0 1-1.5 1.5h-2m-11-8h11");
}

</style>
