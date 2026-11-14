<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1x5kvb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hopscotch" /></template>
<style>
.a1x5kvb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.5h4.5v3.75h2.25V10h-2.25v3.75h2.25v3.75h-2.25v3.75h-4.5V17.5H7.5v-3.75h2.25V10H7.5V6.25h2.25Zm0 3.75h4.5M9.75 10h4.5m-4.5 3.75h4.5m-4.5 3.75h4.5M12 6.25V10m0 3.75v3.75");
}

</style>
