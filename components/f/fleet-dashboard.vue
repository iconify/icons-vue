<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-d4t_byx"/><path class="q-aowxb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fleet-dashboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-aowxb7a {
  d: path("M5.25 9.5L6 5.75h6.5l.75 3.75ZM16 21.5v-3m2.75 3v-6m2.75 6v-4");
}

.v-d4t_byx {
  d: path("M2.5 14.5v-9A2.5 2.5 0 0 1 5 3h8.5A2.5 2.5 0 0 1 16 5.5v9Zm3 0v3m7.5-3v3");
}

</style>
