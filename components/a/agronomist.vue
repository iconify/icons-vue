<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpp_di-uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agronomist" /></template>
<style>
.kpp_di-uq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3.25 21c0-4.5 3-6.75 6.25-6.75c.93 0 1.84.184 2.665.553m3.56 5.492q.024.343.025.705m2.75.5v-3.75m0 .25c0-2-1.5-3-3.5-3c0 2 1.5 3 3.5 3Zm0-.5c0-2 1.5-3 3.5-3c0 2-1.5 3-3.5 3Z");
}

</style>
