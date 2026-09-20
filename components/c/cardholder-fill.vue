<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l5cmc_cws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cardholder-fill" /></template>
<style>
.l5cmc_cws {
  fill: currentColor;
  d: path("M208 48H48a24 24 0 0 0-24 24v112a24 24 0 0 0 24 24h160a24 24 0 0 0 24-24V72a24 24 0 0 0-24-24m-56 72a24 24 0 0 1-48 0a8 8 0 0 0-8-8H40V96h176v16h-56a8 8 0 0 0-8 8M48 64h160a8 8 0 0 1 8 8v8H40v-8a8 8 0 0 1 8-8");
}

</style>
