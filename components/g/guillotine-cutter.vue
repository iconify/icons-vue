<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntob9xbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guillotine-cutter" /></template>
<style>
.ntob9xbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 13h13.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 18.875 20H5.125A2.625 2.625 0 0 1 2.5 17.375v-1.75A2.625 2.625 0 0 1 5.125 13m1.915-1.445l8.729-6.183a1.5 1.5 0 0 1 2.096.364l.016.023a1.5 1.5 0 0 1-.38 2.098l-7.118 4.88a1.5 1.5 0 0 1-.848.263H7.5a.796.796 0 0 1-.46-1.445M18 5.75l3-2.25");
}

</style>
