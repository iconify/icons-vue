<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnrwp2kvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-corner-sharp" /></template>
<style>
.pnrwp2kvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H3V5h18v6M3 5l6 6h6l6-6m-6 13h6m-3-3v6");
}

</style>
