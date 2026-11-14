<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttyyr7bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-audio" /></template>
<style>
.ttyyr7bff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.2 16.5H2.5v-13h19V14M6 8h8m-8 4h5m3 5h1.25l2.25-2v6l-2.25-2H14Zm5.75-.75a2.75 2.75 0 0 1 0 3.5");
}

</style>
