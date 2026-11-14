<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n90wcq-hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gadget-headphones-cover" /></template>
<style>
.n90wcq-hk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12v-.5a7 7 0 0 1 14 0v.5M5.5 12zA2.5 2.5 0 0 1 8 14.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 16v-1.5A2.5 2.5 0 0 1 5.5 12m13 0za2.5 2.5 0 0 1 2.5 2.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 16 16v-1.5a2.5 2.5 0 0 1 2.5-2.5m-6.5.5l2.5 1v1.75c0 1.45-1.1 2.25-2.5 2.75c-1.4-.5-2.5-1.3-2.5-2.75V13.5Z");
}

</style>
