<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzotiobki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-gift-card" /></template>
<style>
.uzotiobki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18v4.5H3Zm1.5 4.5v7a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-7M12 7v13.5M12 7c-2-4-6-3.5-4.5 0M12 7c2-4 6-3.5 4.5 0");
}

</style>
