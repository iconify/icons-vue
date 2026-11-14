<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc3sgybko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-saving-tips" /></template>
<style>
.gc3sgybko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 16v-1.5a6 6 0 1 1 6 0V16Zm.5 2.75h5M9 21.5h3m1-2.75Q16 16 21 17q-2 4.5-8 1.75Z");
}

</style>
