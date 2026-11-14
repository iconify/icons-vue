<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxrshwbpq"/><path class="qxv83mbrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-cog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxrshwbpq {
  d: path("m5.195 9.454l4.5-3.937a3.5 3.5 0 0 1 4.61 0l4.5 3.937A3.5 3.5 0 0 1 20 12.088V16.5a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 16.5v-4.412a3.5 3.5 0 0 1 1.195-2.634");
}

.qxv83mbrw {
  d: path("M11.376 11.303v-.128a.624.624 0 0 1 .624-.62a.624.624 0 0 1 .624.62v.128a.94.94 0 0 0 .469.805a.94.94 0 0 0 .931.003l.111-.064a.624.624 0 0 1 .848.231a.624.624 0 0 1-.225.85l-.11.064a.94.94 0 0 0-.463.808a.94.94 0 0 0 .463.808l.11.064a.624.624 0 0 1 .225.85a.624.624 0 0 1-.848.231l-.111-.064a.94.94 0 0 0-.931.003a.94.94 0 0 0-.469.805v.128a.624.624 0 0 1-.624.62a.624.624 0 0 1-.624-.62v-.128a.94.94 0 0 0-.469-.805a.94.94 0 0 0-.931-.003l-.111.064a.624.624 0 0 1-.848-.231a.624.624 0 0 1 .225-.85l.11-.064A.94.94 0 0 0 9.815 14a.94.94 0 0 0-.463-.808l-.11-.064a.624.624 0 0 1-.225-.85a.624.624 0 0 1 .848-.231l.111.064a.94.94 0 0 0 .931-.003a.94.94 0 0 0 .469-.805");
}

</style>
