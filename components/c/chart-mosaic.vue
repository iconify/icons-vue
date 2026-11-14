<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etuv3obgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-mosaic" /></template>
<style>
.etuv3obgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h5A1.75 1.75 0 0 1 11 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-5a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 4.25 2.5m11 0h4.5a1.75 1.75 0 0 1 1.75 1.75v6A1.75 1.75 0 0 1 19.75 12h-4.5a1.75 1.75 0 0 1-1.75-1.75v-6a1.75 1.75 0 0 1 1.75-1.75m-.375 12za1.375 1.375 0 0 1 1.375 1.375v4.25a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-4.25a1.375 1.375 0 0 1 1.375-1.375m5.25 0za1.375 1.375 0 0 1 1.375 1.375v4.25a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-4.25a1.375 1.375 0 0 1 1.375-1.375");
}

</style>
