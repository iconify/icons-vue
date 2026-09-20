<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lvihmr0_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:battery-vertical-full-bold" /></template>
<style>
.lvihmr0_b {
  fill: currentColor;
  d: path("M92 12a12 12 0 0 1 12-12h48a12 12 0 0 1 0 24h-48a12 12 0 0 1-12-12m112 48v168a28 28 0 0 1-28 28H80a28 28 0 0 1-28-28V60a28 28 0 0 1 28-28h96a28 28 0 0 1 28 28m-24 0a4 4 0 0 0-4-4H80a4 4 0 0 0-4 4v168a4 4 0 0 0 4 4h96a4 4 0 0 0 4-4Zm-24 12h-56a12 12 0 0 0 0 24h56a12 12 0 0 0 0-24m0 40h-56a12 12 0 0 0 0 24h56a12 12 0 0 0 0-24m0 40h-56a12 12 0 0 0 0 24h56a12 12 0 0 0 0-24m0 40h-56a12 12 0 0 0 0 24h56a12 12 0 0 0 0-24");
}

</style>
