<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8_as4a0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gum" /></template>
<style>
.q8_as4a0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5V8a3 3 0 0 1 6 0a3 3 0 0 1 6 0a3 3 0 0 1 6 0v6.5m-18 0q3 3.5 6 0q3 3.5 6 0q3 3.5 6 0V20H3ZM9 8v6.5M15 8v6.5");
}

</style>
