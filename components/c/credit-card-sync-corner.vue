<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtf2u4bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-sync-corner" /></template>
<style>
.dtf2u4bnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V7a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4M3 9h18m0 10a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-7a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

</style>
