<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0fqmsxxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cultural-centre" /></template>
<style>
.x0fqmsxxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6.25l3.587-2.192a1.75 1.75 0 0 1 1.826 0L16.5 6.25A1.484 1.484 0 0 1 15.726 9H8.274A1.484 1.484 0 0 1 7.5 6.25M4.5 18h15a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5A1.5 1.5 0 0 1 4.5 18M12 6.75h.01m-6.01 5V18m4-6.25V18m4-6.25V18m4-6.25V18");
}

</style>
