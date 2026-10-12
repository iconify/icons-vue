<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgb5ubsbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eyebrow-sharp" /></template>
<style>
.qgb5ubsbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5c2.5-3 6-4 9.5-3.25m-8.53 12.3l7.02-7.02l.71-.71l.71.71l1.06 1.06l.71.71l-.71.71l-7.02 7.02l-.71.71l-.71-.71l-1.06-1.06l-.71-.71zm10.38-9.32l1.42 1.42l.53.53l.36-.66l2.23-4.11l.36-.66l-.51.5l-.5.51l-.69.3l-3.04 1.34l-.69.3z");
}

</style>
