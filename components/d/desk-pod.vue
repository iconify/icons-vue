<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sigon5bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desk-pod" /></template>
<style>
.sigon5bjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5v-6h19v6M12 4v10.5M4.75 6h2.5A1.75 1.75 0 0 1 9 7.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 3 8.75v-1A1.75 1.75 0 0 1 4.75 6m12 0h2.5A1.75 1.75 0 0 1 21 7.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 8.75v-1A1.75 1.75 0 0 1 16.75 6M6 10.5v4m12-4v4");
}

</style>
