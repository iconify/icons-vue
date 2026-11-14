<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbrkbx-5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electrical-panel" /></template>
<style>
.wbrkbx-5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h16v19H4ZM7.5 6v3m3-3v3m3-3v3m3-3v3m-9 3v3m3-3v3m3-3v3m3-3v3m-9 3.5h9");
}

</style>
