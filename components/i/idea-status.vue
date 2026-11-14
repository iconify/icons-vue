<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcsmwxbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:idea-status" /></template>
<style>
.fcsmwxbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 16v-1.5c-1.75-1-3-2.9-3-5a5.5 5.5 0 0 1 11 0c0 2.1-1.25 4-3 5V16Zm.5 3.5h4m2.75-1.5l2 2L21 15.75");
}

</style>
