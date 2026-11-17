<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn0hvfm-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-pound-fill-sharp" /></template>
<style>
.sn0hvfm-j {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7-2v1H8a1 1 0 0 0 0 2h1v2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2h-5v-2h2a1 1 0 0 0 0-2h-2v-1a2 2 0 0 1 4 0a1 1 0 0 0 2 0a4 4 0 0 0-8 0");
}

</style>
