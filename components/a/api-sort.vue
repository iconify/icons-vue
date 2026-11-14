<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oque_hkck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-sort" /></template>
<style>
.oque_hkck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H6A1.5 1.5 0 0 0 4.5 5v5.5L3 12l1.5 1.5V19A1.5 1.5 0 0 0 6 20.5h.5M9 7h6.75M9 12h4.5M9 17h2.75M19 3.5v17m-3-3l3 3l3-3");
}

</style>
