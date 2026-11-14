<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nachk63ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-hockey-ball" /></template>
<style>
.nachk63ks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0m7-3h.01m-3.01 3h.01m5.99 0h.01m-3.01 3h.01M2.5 9H5m-2.5 6H5");
}

</style>
