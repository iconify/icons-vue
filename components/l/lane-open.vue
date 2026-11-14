<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afh6hpbaf"/><path class="dokuwgbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-open" /></template>
<style>
.afh6hpbaf {
  d: path("M10.875 2.5h2.25A4.375 4.375 0 0 1 17.5 6.875v.75A4.375 4.375 0 0 1 13.125 12h-2.25A4.375 4.375 0 0 1 6.5 7.625v-.75A4.375 4.375 0 0 1 10.875 2.5M12 12.5V21m-4 0h8");
}

.dokuwgbpb {
  d: path("M10 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.5 0H4m16 0h1.5M3 2.75L4.25 4M21 2.75L19.75 4M3 11.75l1.25-1.25M21 11.75l-1.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
