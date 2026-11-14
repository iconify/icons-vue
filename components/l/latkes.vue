<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x43_zz1el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:latkes" /></template>
<style>
.x43_zz1el {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.375 9h11.25a1.875 1.875 0 0 1 1.875 1.875a1.875 1.875 0 0 1-1.875 1.875H6.375A1.875 1.875 0 0 1 4.5 10.875A1.875 1.875 0 0 1 6.375 9m-1.5 3.75h14.25A1.875 1.875 0 0 1 21 14.625a1.875 1.875 0 0 1-1.875 1.875H4.875A1.875 1.875 0 0 1 3 14.625a1.875 1.875 0 0 1 1.875-1.875m.75 3.75h12.75a1.875 1.875 0 0 1 1.875 1.875a1.875 1.875 0 0 1-1.875 1.875H5.625a1.875 1.875 0 0 1-1.875-1.875A1.875 1.875 0 0 1 5.625 16.5M9 9c0-3 1.75-3 3-5c1.25 2 3 2 3 5");
}

</style>
