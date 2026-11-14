<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekxunjbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-evening" /></template>
<style>
.ekxunjbzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20h18M7.5 20a4.5 4.5 0 0 1 9 0m-9.75-5.25l-1.5-1.5m12 1.5l1.5-1.5M8.993 6.176l4.764-2.75a2.25 2.25 0 0 1 3.073.824a2.25 2.25 0 0 1-.823 3.074l-4.764 2.75A2.25 2.25 0 0 1 8.17 9.25a2.25 2.25 0 0 1 .823-3.074m2.382-1.375l2.25 3.898");
}

</style>
