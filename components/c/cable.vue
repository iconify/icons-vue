<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkj8ddsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable" /></template>
<style>
.hlkj8ddsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6h8v6H8Zm2-3.5V6m4-3.5V6m-2 6c0 3.5-7.5 2.5-7.5 6s10.5 3.5 15-.5");
}

</style>
