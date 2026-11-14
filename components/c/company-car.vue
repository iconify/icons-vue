<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqm8n1bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-car" /></template>
<style>
.xqm8n1bga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 10.5l1.25-4c.25-.9 1-1.5 2-1.5h6.5c1 0 1.75.6 2 1.5l1.25 4M3 10.5h18V17H3ZM6 17v2.5M18 17v2.5M6.75 13.75h.01m10.49 0h.01M10.5 14h3");
}

</style>
