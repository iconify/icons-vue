<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om91cn4mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:awareness-ribbon-check" /></template>
<style>
.om91cn4mt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 21l7-9.5c1.75-2.5 1.5-9-2.5-9s-4.25 6.5-2.5 9l7 9.5m1.25-3l2 2L21 15.75");
}

</style>
