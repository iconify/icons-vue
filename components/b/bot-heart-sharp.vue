<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zpv4lqb3x"/><path class="onpfuibrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-heart-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onpfuibrt {
  d: path("M11.8705 7.7535L12.5816 12.4178M15.8248 7.1507L16.5359 11.815");
}

.zpv4lqb3x {
  d: path("M12 21C7.4376 17.1033 2 13.75 2 8.75C2 5.5743 4.6862 3 8 3C9.5 3 10.8426 3.5459 12 4.5C13.1574 3.5459 14.5 3 16 3C19.3138 3 22 5.5743 22 8.75C22 13.75 16.5624 17.1033 12 21Z");
}

</style>
