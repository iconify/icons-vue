<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guz2p0bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:list-hygiene" /></template>
<style>
.guz2p0bpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M3 9.5h18M3 15h8.5m6.25-1q.5 3.25 3.75 3.75q-3.25.5-3.75 3.75q-.5-3.25-3.75-3.75q3.25-.5 3.75-3.75Z");
}

</style>
