<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bamux0boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:creditors-list" /></template>
<style>
.bamux0boa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h.01M4 9.5h.01m-.01 6h.01M8 3.5h12m-12 6h12m-12 6h3.5M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

</style>
