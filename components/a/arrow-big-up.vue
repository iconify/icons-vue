<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnot4-svi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-big-up" /></template>
<style>
.bnot4-svi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.99 3.99l6.77 6.77q.99.99-.41.99H16.9q-1.4 0-1.4 1.4v6.2q0 1.4-1.4 1.4H9.9q-1.4 0-1.4-1.4v-6.2q0-1.4-1.4-1.4H4.65q-1.4 0-.41-.99l6.77-6.77q.99-.99 1.98 0");
}

</style>
