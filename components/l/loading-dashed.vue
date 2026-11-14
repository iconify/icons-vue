<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fel4ag08t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading-dashed" /></template>
<style>
.fel4ag08t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5a9.5 9.5 0 0 1 6.718 16.218m-3.469 2.209A9.5 9.5 0 0 1 12 21.5m-4.015-.89a9.5 9.5 0 0 1-2.703-1.892m-2.209-3.469A9.5 9.5 0 0 1 2.5 12m.89-4.015a9.5 9.5 0 0 1 1.892-2.703");
}

</style>
