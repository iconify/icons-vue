<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8s2ht4rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-bar" /></template>
<style>
.g8s2ht4rt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5M8 17.25v-5m3.5 5v-9m3.5 9v-12m3.5 12v-3.5");
}

</style>
