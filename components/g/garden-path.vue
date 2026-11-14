<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sft-b9muy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-path" /></template>
<style>
.sft-b9muy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5a4.5 2.5 0 1 0 9 0a4.5 2.5 0 1 0-9 0Zm7-6.5a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0ZM7 5.5a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0Z");
}

</style>
