<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9skfwv9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:end-to-end-encryption" /></template>
<style>
.q9skfwv9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 6h.25A2.625 2.625 0 0 1 8 8.625v6.75A2.625 2.625 0 0 1 5.375 18h-.25A2.625 2.625 0 0 1 2.5 15.375v-6.75A2.625 2.625 0 0 1 5.125 6m13.5 0h.25A2.625 2.625 0 0 1 21.5 8.625v6.75A2.625 2.625 0 0 1 18.875 18h-.25A2.625 2.625 0 0 1 16 15.375v-6.75A2.625 2.625 0 0 1 18.625 6M11 11h2a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 13 16h-2a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 11 11m-.75 0V9.75a1.75 1.75 0 0 1 3.5 0V11");
}

</style>
