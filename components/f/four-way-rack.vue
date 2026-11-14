<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubkky4f6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:four-way-rack" /></template>
<style>
.ubkky4f6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v17m-5 2h10m-5-2v2M4.5 5H12m0 6h7.5m-14-4v-.75A1.25 1.25 0 1 0 4.25 5m-1.5 3.5L4.5 7h2l1.75 1.5l-.75 1.75L7 10v4.5H4V10l-.5.25ZM18.5 13v-.75A1.25 1.25 0 1 0 17.25 11m-1.5 3.5L17.5 13h2l1.75 1.5l-.75 1.75L20 16v4.5h-3V16l-.5.25Z");
}

</style>
