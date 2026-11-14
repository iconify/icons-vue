<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqjzfab8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apartment-building" /></template>
<style>
.jqjzfab8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h8v13h-8Zm8-5h9v18h-9ZM6 12h1m-1 4h1m7-9h1m-1 4h1m2-4h1m-1 4h1");
}

</style>
