<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g_s-lzb5n"/><path class="rqphtbcee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-expand-all" /></template>
<style>
.g_s-lzb5n {
  d: path("M11.9 19H3V2.5h13V12");
}

.rqphtbcee {
  d: path("M8.5 8L6 10.75l2.5 2.75m2-5.5l2.5 2.75l-2.5 2.75m5 2.5l3-2.5l3 2.5m-6 3l3 2.5l3-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
