<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxjeh9kji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-stock-up" /></template>
<style>
.sxjeh9kji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.3431 4.3431 3 6 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6ZM3 15L7 11L10 14L15 9L17 11L21 7");
}

</style>
