<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djh78xp0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-bundle-save" /></template>
<style>
.djh78xp0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5h7.25v11.5H3.25Zm10 9V5h7.25v6.45M2 10.75h20M6.75 5v2.5m10-2.5v2.5m-.25 6.75h5.25v7.5H16.5L13.75 18Zm.25 3.75h.01");
}

</style>
