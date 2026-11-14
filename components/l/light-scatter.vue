<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skntpqbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-scatter" /></template>
<style>
.skntpqbay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8 0h6m-7.25-3.5l4.25-3.75M14.25 15.5l4.25 3.75");
}

</style>
