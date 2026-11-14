<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhb9kjbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:computer-repair" /></template>
<style>
.mhb9kjbkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.7 16.5H2.5v-13h19v8.4M12 16.5v3.6m-4 .4h3.6m7.65-6a2.5 2.5 0 1 0 2.25 2.25m-4.25 2l-2.5 2.5");
}

</style>
