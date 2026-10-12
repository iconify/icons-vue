<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afea55bzh"/><path class="ro0e9_bbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:construction-zone" /></template>
<style>
.afea55bzh {
  d: path("m13.24 3.99l6.77 6.77q1.24 1.24 0 2.48l-6.77 6.77q-1.24 1.24-2.48 0l-6.77-6.77q-1.24-1.24 0-2.48l6.77-6.77q1.24-1.24 2.48 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ro0e9_bbz {
  d: path("M8.25 14.75h7.5m-6.75 0a3 3 0 0 1 6 0");
}

</style>
