<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db2wmhbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-sprig-pair" /></template>
<style>
.db2wmhbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 21l8-8m0 0c0-4 3.5-7.5 7.5-7.5c0 4-3.5 7.5-7.5 7.5Zm-4 4c-3-2-4.5-6.5-3.5-10.5C9 8.5 10.5 13 9 17Z");
}

</style>
