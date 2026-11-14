<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s82vw2bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-building" /></template>
<style>
.s82vw2bjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9a5.5 5.5 0 0 1 11 0m-14 0h17M3 20h18M12 2v1.5m-5.5 8.25v5.5m3.75-5.5v5.5m3.5-5.5v5.5m3.75-5.5v5.5");
}

</style>
