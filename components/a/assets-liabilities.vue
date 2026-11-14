<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_xq-b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assets-liabilities" /></template>
<style>
.px_xq-b0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16.5m-3.5 0h7M5.5 7h13m-13 0l-3 7h6l-3-7m-3 7a3 3 0 0 0 6 0m10-7l-3 7h6l-3-7m-3 7a3 3 0 0 0 6 0");
}

</style>
