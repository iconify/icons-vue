<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqvtt2tir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-cargo-uld" /></template>
<style>
.kqvtt2tir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20V6a2 2 0 0 1 2-2h9l7 7v7a2 2 0 0 1-2 2Zm0-3.5h18M12 4v12.5");
}

</style>
