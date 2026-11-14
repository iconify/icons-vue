<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kopz6bc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bill-of-materials" /></template>
<style>
.kopz6bc2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.75h6v5H9Zm3 5v6.5m-7.25 0v-3h14.5v3m-16.75 0H7v5H2.5Zm7.25 0h4.5v5h-4.5Zm7.25 0h4.5v5H17Z");
}

</style>
