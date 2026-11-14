<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s81sl9bas"/><path class="sh1e9xg1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-tower-alert" /></template>
<style>
.s81sl9bas {
  d: path("M4.5 19.5L10 7l5.213 11.847");
}

.sh1e9xg1j {
  d: path("M8.5 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.25 7.75h5.5m1.08-10.964a5 5 0 0 1 0 6.428m-7.66 0a5 5 0 0 1 0-6.428M18 14.5V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
