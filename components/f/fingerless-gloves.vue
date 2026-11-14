<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwee5wbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fingerless-gloves" /></template>
<style>
.cwee5wbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21v-8l-3-2.75c-1-1 .25-2.75 1.5-1.75L8 9.75V7h9.75v14ZM8 7V5.5a1.625 1.625 0 0 1 3.25 0V7m0-1.5a1.625 1.625 0 0 1 3.25 0V7m0-1.5a1.625 1.625 0 0 1 3.25 0V7M8 17h9.75");
}

</style>
