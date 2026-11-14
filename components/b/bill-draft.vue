<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu7bd1juj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bill-draft" /></template>
<style>
.xu7bd1juj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.3V4h8.1M18 9.9v11.6H4v-1.9m2.5-4.1L8 12L18 2l2 2l-10 10ZM8 12l2 2");
}

</style>
