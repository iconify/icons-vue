<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gp-vm0nuh"/><path class="koed9k3qm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concert-ticket" /></template>
<style>
.gp-vm0nuh {
  d: path("M5.125 5.5h7.25A2.625 2.625 0 0 1 15 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625h-7.25A2.625 2.625 0 0 1 2.5 15.875v-7.75A2.625 2.625 0 0 1 5.125 5.5m14.375 0h.25a1.75 1.75 0 0 1 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75h-.25a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 19.5 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.koed9k3qm {
  d: path("M6.25 14.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3 0v-6q3 .75 2.75 3.25");
}

</style>
