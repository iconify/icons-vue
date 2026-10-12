<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdv-2s2ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flat-sign" /></template>
<style>
.cdv-2s2ve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75V20.5m0-7.25c1.9-1.85 3.7-3 5.6-3c1.95 0 3.4 1.2 3.4 3.1c0 3.35-4.75 5.55-9 7.15");
}

</style>
