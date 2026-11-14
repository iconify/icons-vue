<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb7of8ogb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-code" /></template>
<style>
.tb7of8ogb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.871 4.386l6.718 6.718l-8.485 8.485l-6.718-6.718l.707-7.778ZM8.275 8.275h.01m4.056 1.238l2.475 2.474m-5.303.354l2.474 2.475");
}

</style>
