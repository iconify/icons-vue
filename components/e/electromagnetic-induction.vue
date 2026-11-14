<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mioogqyzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electromagnetic-induction" /></template>
<style>
.mioogqyzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h8v5h-8ZM13 5a2 7 0 0 1 0 14m3.25-14a2 7 0 0 1 0 14M19.5 5a2 7 0 0 1 0 14m-13-6v5M3 8h7M8 6l2 2l-2 2");
}

</style>
