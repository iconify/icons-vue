<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8yjc5b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:change-data-capture" /></template>
<style>
.b8yjc5b8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.404 7.245l3.836 10.228a1.5 1.5 0 0 1-1.405 2.027h-7.67a1.5 1.5 0 0 1-1.405-2.027L6.596 7.245a1.5 1.5 0 0 1 2.808 0M16.25 16.5h.01m2.49 0h.01m2.49 0h.01");
}

</style>
