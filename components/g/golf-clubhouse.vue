<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0b_8bcdp"/><path class="ixv163bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-clubhouse" /></template>
<style>
.h0b_8bcdp {
  d: path("M3.5 13L12 8l8.5 5v8h-17ZM12 8V2.5m0 0l5 1.75L12 6Z");
}

.ixv163bsh {
  d: path("M10 21v-4h4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
