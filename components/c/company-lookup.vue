<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrlfhwbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-lookup" /></template>
<style>
.yrlfhwbvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.4 20.25H4V6.5h2.5v-4h6v4H15v6.15M7.5 9.5h.01m3.99 0h.01m-4.01 3h.01m3.99 0h.01m-4.01 3h.01m3.99 0h.01m2.24 2.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm4.75 2l1.75 1.75");
}

</style>
