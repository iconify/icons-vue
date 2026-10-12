<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe8rwobur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:extension-house" /></template>
<style>
.qe8rwobur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V8.85q0-1 .74-1.67l3.65-3.26q.74-.67 1.48 0l3.64 3.26q.74.67.74 1.67v11.4q0 1-1 1H3.75q-1 0-1-1M16 20.5v-8.75q0-.75.71-.51l3.83 1.27q.71.24.71.99v7q0 .75-.75.75h-3.75q-.75 0-.75-.75m2.63-5.25v3.5M16.88 17h3.5");
}

</style>
