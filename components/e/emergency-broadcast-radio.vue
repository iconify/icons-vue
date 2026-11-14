<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xslmiibao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-broadcast-radio" /></template>
<style>
.xslmiibao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.5L12 10l2.5 11.5M12 7h.01M9.25 5a3.5 3.5 0 0 0 0 4m5.5-4a3.5 3.5 0 0 1 0 4M7 2.75a6.5 6.5 0 0 0 0 8.5m10-8.5a6.5 6.5 0 0 1 0 8.5");
}

</style>
