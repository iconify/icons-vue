<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhrdf4sqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-sealer" /></template>
<style>
.vhrdf4sqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h14.5A1.75 1.75 0 0 1 21 4.75v.5A1.75 1.75 0 0 1 19.25 7H4.75A1.75 1.75 0 0 1 3 5.25v-.5A1.75 1.75 0 0 1 4.75 3m.75 4l-1 12.5A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-1.5L18.5 7m-10-4v4M12 3v4m3.5-4v4");
}

</style>
