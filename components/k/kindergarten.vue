<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu5c417ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kindergarten" /></template>
<style>
.pu5c417ka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 12.5h4A1.75 1.75 0 0 1 11 14.25v4.5a1.75 1.75 0 0 1-1.75 1.75h-4a1.75 1.75 0 0 1-1.75-1.75v-4.5a1.75 1.75 0 0 1 1.75-1.75m9.5 0h4a1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75h-4A1.75 1.75 0 0 1 13 18.75v-4.5a1.75 1.75 0 0 1 1.75-1.75M8.711 7.063l2.003-2.17a1.75 1.75 0 0 1 2.572 0l2.003 2.17A1.75 1.75 0 0 1 14.003 10H9.997a1.75 1.75 0 0 1-1.286-2.937M7.25 16.5h.01m9.49 0h.01");
}

</style>
