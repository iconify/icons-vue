<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gesnncbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:logic-bomb" /></template>
<style>
.gesnncbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m10.5-4.5l2.75-2.75M17.5 3v1.5m3 2H19m1-2.75l-1 1M10.5 14v-3m0 3l2.5 1.25");
}

</style>
