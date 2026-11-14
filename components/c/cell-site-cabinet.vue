<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8hl-bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cell-site-cabinet" /></template>
<style>
.ip8hl-bch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 7h8.5A1.75 1.75 0 0 1 18 8.75v11a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 19.75v-11A1.75 1.75 0 0 1 7.75 7M15 7V4.25M12 7v14.5m-3-9v3m5-12.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
