<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xku04_bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bitcoin-sharp" /></template>
<style>
.xku04_bup {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 20L5 19L5 5L15.5 5C17.433 5 19 6.567 19 8.5C19 10.433 17.433 12 15.5 12L5 12L4 12M4 12L5 12L15.5 12C17.433 12 19 13.567 19 15.5C19 17.433 17.433 19 15.5 19L5 19L4 19M10 1L10 2L10 5L10 6M15.5 1L15.5 2L15.5 5L15.5 6M10 18L10 19L10 22L10 23M15.5 18L15.5 19L15.5 22L15.5 23");
}

</style>
