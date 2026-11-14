<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_pzy-6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-merch" /></template>
<style>
.h2_pzy-6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5L3 6.5L4.5 11L7 10v10.5h10V10l2.5 1L21 6.5l-5.5-3C15 5.25 13.75 6 12 6s-3-.75-3.5-2.5ZM7 15.5h10");
}

</style>
