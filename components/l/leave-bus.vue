<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c-i3sh0ed"/><path class="sa7nwymsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-bus" /></template>
<style>
.c-i3sh0ed {
  d: path("M2.5 2.5h11V19h-11Zm0 6.5h11M5 19v2.5m6-2.5v2.5m5.25-15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.sa7nwymsn {
  d: path("m18.5 8.75l-1 6.25l-1.25 6.5M17.5 15l3 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
