<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf9e69bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-chores" /></template>
<style>
.pf9e69bwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.5V14m-2.959 5.753l.75-4.5A1.5 1.5 0 0 1 5.521 14h1.458a1.5 1.5 0 0 1 1.48 1.253l.75 4.5a1.5 1.5 0 0 1-1.48 1.747H4.771a1.5 1.5 0 0 1-1.48-1.747M16.625 9.625l.226.587a1.75 1.75 0 0 0 1.508 1.117l.641.046a.698.698 0 0 1 .392 1.236l-.482.394a1.75 1.75 0 0 0-.564 1.869l.154.501a.606.606 0 0 1-.915.682l-.614-.41a1.75 1.75 0 0 0-1.942 0l-.614.41a.606.606 0 0 1-.915-.682l.154-.501a1.75 1.75 0 0 0-.564-1.869l-.482-.394A.698.698 0 0 1 13 11.375l.641-.046a1.75 1.75 0 0 0 1.508-1.117l.226-.587a.67.67 0 0 1 1.25 0");
}

</style>
