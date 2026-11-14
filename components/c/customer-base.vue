<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd3zohb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-base" /></template>
<style>
.fd3zohb1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM7 19c0-3.5 2.25-6 5-6s5 2.5 5 6M2.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 9c0-2.5.75-4 2.25-4.25M17.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 9c0-2.5-.75-4-2.25-4.25");
}

</style>
