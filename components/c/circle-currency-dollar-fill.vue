<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzqouzyen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-dollar-fill" /></template>
<style>
.lzqouzyen {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m11-5V6a1 1 0 0 0-2 0v1a3 3 0 1 0 0 6h2a1 1 0 0 1 0 2h-3a1 1 0 0 0-2 0a2 2 0 0 0 2 2h1v1a1 1 0 0 0 2 0v-1a3 3 0 1 0 0-6h-2a1 1 0 0 1 0-2h3a1 1 0 0 0 2 0a2 2 0 0 0-2-2Z");
}

</style>
