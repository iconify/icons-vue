<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geh6pke9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:http-insecure" /></template>
<style>
.geh6pke9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 19.5H3v-10h12.5v2.2M6.25 9.5V6a3.5 3.5 0 0 1 7 0v1M18 14.5V18m0 3h.01");
}

</style>
