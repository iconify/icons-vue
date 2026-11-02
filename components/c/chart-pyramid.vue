<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu8480blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid" /></template>
<style>
.zu8480blb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 11l4 8c.46.919-.081 2-1 2H5c-.919 0-1.46-1.081-1-2l7-14a1.118 1.118 0 0 1 2 0zM9 9h6m-9 6h12");
}

</style>
