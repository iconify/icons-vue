<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ryupnmnrb"/><path class="hiu57r88u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:igloo-hotel" /></template>
<style>
.hiu57r88u {
  d: path("M9.5 19v-3c0-2 5-2 5 0v3m-11-6.5h17");
}

.ryupnmnrb {
  d: path("M3.5 19C3.5 11 7 6 12 6s8.5 5 8.5 13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
