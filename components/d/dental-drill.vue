<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eijqsdb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dental-drill" /></template>
<style>
.eijqsdb-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.08 18.19l4.42-6.82q.54-.84 1.38-1.38l4.78-3.05q.84-.54.84-1.54v-.15q0-1 1-1H19q1 0 1 1V9.5q0 1-1 1h-2q-1 0-1.91.41l-2.58 1.18q-.91.41-1.43 1.26l-4.1 6.77q-.52.85-1.35.3l-1.26-.84q-.83-.55-.29-1.39M17.5 10.5v3.75m2.75-1.5L21 14.5");
}

</style>
