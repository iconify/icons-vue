<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crm70y75p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-error-bars" /></template>
<style>
.crm70y75p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5v14m6-15v10m6-6v9M4.5 5h3m-3 14h3m3-15h3m-3 10h3m3-6h3m-3 9h3M6 12h.01M12 9h.01M18 12.5h.01");
}

</style>
