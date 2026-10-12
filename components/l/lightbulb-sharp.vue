<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbvmnxbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lightbulb-sharp" /></template>
<style>
.xbvmnxbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 17.25v-1.5a3 3 0 0 0-1.1-2.3a6 6 0 1 1 7.7 0a3 3 0 0 0-1.1 2.3v1.5Zm.5 3.25h4.5");
}

</style>
