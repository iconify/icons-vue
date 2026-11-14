<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0nzq6ymg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binaural-audio" /></template>
<style>
.n0nzq6ymg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 13v-2a7.25 7.25 0 0 1 14.5 0v2M2.5 13H7v7H2.5ZM17 13h4.5v7H17Zm-7.5.5a5 5 0 0 1 0 6m5-6a5 5 0 0 0 0 6");
}

</style>
