<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9s_sl9lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:function-layer" /></template>
<style>
.x9s_sl9lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l8.5 4.5L12 12L3.5 7.5Zm-8.5 9.5L12 17l.957-.506m5.921-3.135L20.5 12.5m-4.75 3H17l4.25 6m-2.75-3.25l-2.75 3.25");
}

</style>
