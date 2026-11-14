<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocd7n2b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-energy" /></template>
<style>
.ocd7n2b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M12 2.5v2.25m0 14.5v2.25M2.5 12h2.25m14.5 0h2.25M6.75 6.75l-1.5-1.5m12 1.5l1.5-1.5m-12 12l-1.5 1.5m12-1.5l1.5 1.5");
}

</style>
