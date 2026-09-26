<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mueb7hbap"/><path class="qpoj1zb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mueb7hbap {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 22C8.0711 22 10 20.0711 10 18C10 15.9289 8.0711 14 6 14C3.9289 14 2 15.9289 2 18C2 20.0711 3.9289 22 6 22ZM18 10C20.0711 10 22 8.0711 22 6C22 3.9289 20.0711 2 18 2C15.9289 2 14 3.9289 14 6C14 8.0711 15.9289 10 18 10Z");
  stroke: none;
}

.qpoj1zb_h {
  d: path("M6 2L6 15C6.1667 12 8.2 6 15 6M6 21C7.6569 21 9 19.6569 9 18C9 16.3431 7.6569 15 6 15C4.3431 15 3 16.3431 3 18C3 19.6569 4.3431 21 6 21ZM18 9C19.6569 9 21 7.6569 21 6C21 4.3431 19.6569 3 18 3C16.3431 3 15 4.3431 15 6C15 7.6569 16.3431 9 18 9Z");
}

</style>
