<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6_92fb_t"/><path class="in41_ubsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-two-tone" /></template>
<style>
.in41_ubsa {
  d: path("M17.1716 3.5858L21.4142 7.8284C22.1952 8.6095 22.1952 9.8758 21.4142 10.6569L11.0711 21L5.4142 21L2.5858 18.1716C1.8047 17.3905 1.8047 16.1242 2.5858 15.3431L14.3431 3.5858C15.1242 2.8047 16.3905 2.8047 17.1716 3.5858ZM8 9.9289L15.0711 17M8.2427 21L22 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6_92fb_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.4853 20L22 20C22.5523 20 23 20.4477 23 21C23 21.5523 22.5523 22 22 22L5.4142 22C5.149 22 4.8947 21.8946 4.7071 21.7071L1.8787 18.8787C1.3161 18.3161 1 17.553 1 16.7573C1 15.9617 1.3161 15.1986 1.8787 14.636L13.636 2.8787C14.1986 2.3161 14.9617 2 15.7573 2C16.553 2 17.3161 2.3161 17.8787 2.8787L22.1213 7.1213C22.6839 7.6839 23 8.447 23 9.2427C23 10.0383 22.6839 10.8014 22.1213 11.364L13.4853 20Z");
  stroke: none;
}

</style>
