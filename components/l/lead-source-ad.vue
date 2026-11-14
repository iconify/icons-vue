<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwtziibow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-source-ad" /></template>
<style>
.nwtziibow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.5h1.785a2.6 2.6 0 0 0 1.331-.362l3.928-2.311A2.625 2.625 0 0 1 16 8.09v7.82a2.625 2.625 0 0 1-3.956 2.263l-3.928-2.311a2.6 2.6 0 0 0-1.331-.362H5A2.5 2.5 0 0 1 2.5 13v-2A2.5 2.5 0 0 1 5 8.5m.5 7l1.5 5M19 9a4 4 0 0 1 0 6");
}

</style>
