<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhvwcybps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-solana-fill-sharp" /></template>
<style>
.bhvwcybps {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M15 6h-5a1 1 0 0 0-.707.293l-1 1A1 1 0 0 0 9 9h5c.265 0 .52-.105.707-.293l1-1A1 1 0 0 0 15 6m-1 4H8a1.002 1.002 0 0 0-.707 1.707l2 2A1 1 0 0 0 10 14h6a1.002 1.002 0 0 0 .707-1.707l-2-2A1 1 0 0 0 14 10m-4 5a1 1 0 0 0-.707.293l-1 1A1 1 0 0 0 9 18h5c.265 0 .52-.105.707-.293l1-1A1 1 0 0 0 15 15Z");
}

</style>
