<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1o_w8n_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chameleon" /></template>
<style>
.u1o_w8n_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12.5c.5-4 4-6 7.5-5.5l2.25-2.5L19.5 8c1.25.75 2 2 1.5 3s-2 1.25-3.5 1.25c-3 1.75-7 2.5-9.5.25m0 0c-3.5 0-5 2-5 4.25c0 2.5 2 4 4 3.25c1.75-.75 1.75-3.5-.25-3.75c-1-.15-1.5.75-1.25 1.5m5 2.75l11-4.5m-8.75-2.25v5.75m3.75-6.75V18m.75-8.25h.01");
}

</style>
