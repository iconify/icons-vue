<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfmugbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:image-placeholder" /></template>
<style>
.nsfmugbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.25V5.5a2 2 0 0 1 2-2h2m3.5 0h4m3.5 0h2a2 2 0 0 1 2 2v1.75m0 2.75v4m0 2.75v1.75a2 2 0 0 1-2 2h-2m-3.5 0h-4m-3.5 0h-2a2 2 0 0 1-2-2v-1.75m0-2.75v-4m3 7.5l4.5-5l3.5 3.5l2-2l3 3.5m-4-9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
