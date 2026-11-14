<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atk9tsaml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:board-room-table" /></template>
<style>
.atk9tsaml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8.75h14.5A1.25 1.25 0 0 1 20.5 10v4a1.25 1.25 0 0 1-1.25 1.25H4.75A1.25 1.25 0 0 1 3.5 14v-4a1.25 1.25 0 0 1 1.25-1.25ZM6.5 6H10m4 0h3.5m-11 12H10m4 0h3.5");
}

</style>
