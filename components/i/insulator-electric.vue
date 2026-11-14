<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtjwqv_1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insulator-electric" /></template>
<style>
.xtjwqv_1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5h2A3.5 3.5 0 0 1 16.5 8v8a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 7.5 16V8A3.5 3.5 0 0 1 11 4.5M2.5 12h5m9 0h5m-14-2.75h9m-9 5.5h9");
}

</style>
