<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg5n30bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:base64" /></template>
<style>
.fg5n30bpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h8v11.5h-8Zm11 0h8v11.5h-8ZM5 13h3m-3 2.75h3M5 18.5h2m9-2.75h.01m2.99 0h.01M6.5 7.25c1-4.5 10-4.5 11 0m-1.75-1l1.75 1l1-1.75");
}

</style>
