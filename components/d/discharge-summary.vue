<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnp6sccpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discharge-summary" /></template>
<style>
.dnp6sccpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.9 19H3V2.5h13v8.9M6 7h7m-7 3.5h7M6 14h4.5m8.5 2v-1.75h-4.25v7.5H19V20m-2-2h4.5M20 16.5l1.5 1.5l-1.5 1.5");
}

</style>
