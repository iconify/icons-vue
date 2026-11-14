<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0sirntqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canonical-link" /></template>
<style>
.p0sirntqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 10.25L4 13a3.5 3.5 0 0 0 5 5l2.75-2.75m3.5-3.5L18 9a3.5 3.5 0 0 0-5-5l-2.75 2.75m-2.5 7.5l6.5-6.5m.5 10.25l2 2L21 15.75");
}

</style>
