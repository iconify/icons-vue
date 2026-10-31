<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h0eqbkbhb"/><path class="uxh9t0b0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-text-cursor-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h0eqbkbhb {
  stroke-opacity: 0.4;
  d: path("M1.9417 19.6637L7.1788 5L12.4158 19.6637M3.9645 14L10.3931 14");
}

.uxh9t0b0w {
  d: path("M19 5.8C18.6667 5.35 17.6 4 16 4L15 4M19 5.8C19.3333 5.35 20.4 4 22 4L23 4M19 5.8L19 18.2M19 18.2C19.3333 18.65 20.4 20 22 20L23 20M19 18.2C18.6667 18.65 17.6 20 16 20L15 20");
}

</style>
