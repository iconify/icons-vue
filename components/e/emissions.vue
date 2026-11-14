<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t89-ebr-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emissions" /></template>
<style>
.t89-ebr-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20v-7H4V9.5h3V13h5V9.5h3V13l3-2.5V13l3.5-2.5V20Zm1-14.75a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0Zm8 0a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0Z");
}

</style>
