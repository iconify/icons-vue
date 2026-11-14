<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnadvccrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-skeleton" /></template>
<style>
.fnadvccrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 0H21m-4.75 0v3.75h2.25V14H21v-2");
}

</style>
