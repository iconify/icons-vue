<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ais8kfbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf" /></template>
<style>
.ais8kfbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11V5c0-.919 1.081-1.46 2-1l4 2a1.118 1.118 0 0 1 0 2zm0 0v6m-4 2c0 1.105 1.79 2 4 2s4-.895 4-2");
}

</style>
