<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtq4febbd"/><path class="knlz_6bba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incident-root-cause" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knlz_6bba {
  d: path("M3 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m17-4V18m0 3h.01");
}

.vtq4febbd {
  d: path("M10 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3v3m-7 4v-4h14");
}

</style>
