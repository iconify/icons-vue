<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zogemjb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-bow" /></template>
<style>
.zogemjb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13c-4-6-9-5-8-2s5 3 8 2Zm0 0c4-6 9-5 8-2s-5 3-8 2Zm0 0l-3 7.5m3-7.5l3 7.5");
}

</style>
