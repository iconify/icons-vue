<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvvgtub4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-blower" /></template>
<style>
.gvvgtub4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 4h.75A2.625 2.625 0 0 1 8.5 6.625v2.25A2.625 2.625 0 0 1 5.875 11.5h-.75A2.625 2.625 0 0 1 2.5 8.875v-2.25A2.625 2.625 0 0 1 5.125 4m5.078 2.232l2.806.383A1.146 1.146 0 0 1 14 7.75a1.146 1.146 0 0 1-.991 1.135l-2.806.383A1.5 1.5 0 0 1 8.5 7.782v-.064a1.5 1.5 0 0 1 1.703-1.486M13 20.5c0-4 3-6.5 7.5-6.5c0 4-3 6.5-7.5 6.5m3.75-14.25h4.75m-4.75 3H20");
}

</style>
