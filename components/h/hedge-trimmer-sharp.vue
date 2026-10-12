<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rak2dcczq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hedge-trimmer-sharp" /></template>
<style>
.rak2dcczq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.48 8.68l3.54.64l.98.18v5l-.98.18l-3.54.64l-.98.18v-7zM5.5 9.75H2.75v4.5H5.5M11 10.5l1.46-2l1.46 2l1.46-2l1.46 2l1.46-2l1.46 2h1.5v3h-1.5l-1.46 2l-1.46-2l-1.46 2l-1.46-2l-1.46 2l-1.46-2Z");
}

</style>
