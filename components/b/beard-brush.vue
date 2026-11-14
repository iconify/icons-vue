<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc6wywmex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beard-brush" /></template>
<style>
.fc6wywmex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.621 3.843l3.536 3.536a1.5 1.5 0 0 1 0 2.121L14.5 15.157a1.5 1.5 0 0 1-2.121 0l-3.536-3.536a1.5 1.5 0 0 1 0-2.121L14.5 3.843a1.5 1.5 0 0 1 2.121 0Zm-7.323 8.738l2.121 2.121l-6.717 6.717l-2.121-2.121ZM16.75 7.25h.01M14.5 9.5h.01m-2.26 2.25h.01");
}

</style>
