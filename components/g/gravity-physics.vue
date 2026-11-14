<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfl0u1-0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gravity-physics" /></template>
<style>
.yfl0u1-0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 20.5h18M18 5v10m-2.5-2.5L18 15l2.5-2.5");
}

</style>
