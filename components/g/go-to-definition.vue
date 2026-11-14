<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzq0oi24o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:go-to-definition" /></template>
<style>
.kzq0oi24o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h6m-3-3l3 3l-3 3m6-11h10m-7.375 5h4.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 18.875 15h-4.75a2.625 2.625 0 0 1-2.625-2.625v-.75A2.625 2.625 0 0 1 14.125 9m.125 3h4.5m-7.25 8h6");
}

</style>
