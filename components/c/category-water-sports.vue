<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-qykbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-water-sports" /></template>
<style>
.yz-qykbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13C5 10 7 10 9 12q3 3 6 0c2-2 4-2 6.5 1m-19 5C5 15 7 15 9 17q3 3 6 0c2-2 4-2 6.5 1M12 4v5");
}

</style>
