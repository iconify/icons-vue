<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vim-_3b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-candlestick-sharp" /></template>
<style>
.vim-_3b2r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L3 21L22 21M7 5L11 5L11 10L7 10L7 5ZM15 9L19 9L19 15L15 15L15 9ZM9 2L9 5M9 10L9 14M17 5L17 9M17 15L17 18");
}

</style>
