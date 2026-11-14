<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr1i42ifv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-feed" /></template>
<style>
.hr1i42ifv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14c1.6-2.55 3.55-3.52 5.25-3.5c2.2-.02 3.83 1.6 4.5 3.5c-.67 2-2.3 3.63-4.5 3.75c-1.7-.12-3.65-1.1-5.25-3.75Zm0 0L6 11.5v5.25Zm6.75-1h.01M8 4h.01M12 6h.01M16 4h.01");
}

</style>
