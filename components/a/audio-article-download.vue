<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx-pmpxmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-article-download" /></template>
<style>
.nx-pmpxmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5v5M7.5 5v14M12 2.5v15.1m0 1.8v2.1M16.5 5v6.7M21 8v3.5m-3 3v7m-3-3l3 3l3-3");
}

</style>
