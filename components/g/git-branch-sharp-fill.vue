<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e7l5ofdkm"/><path class="rsvzw6bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-sharp-fill" /></template>
<style>
.e7l5ofdkm {
  d: path("M6 22L6 9C6.1667 12 8.2 18 15 18L16 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsvzw6bws {
  fill: currentColor;
  d: path("M6 10C3.9289 10 2 8.0711 2 6C2 3.9289 3.9289 2 6 2C8.0711 2 10 3.9289 10 6C10 8.0711 8.0711 10 6 10ZM18 22C15.9289 22 14 20.0711 14 18C14 15.9289 15.9289 14 18 14C20.0711 14 22 15.9289 22 18C22 20.0711 20.0711 22 18 22Z");
  stroke: none;
}

</style>
