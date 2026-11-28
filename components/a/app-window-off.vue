<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mx2lwm0ju"/><path class="q7kx8tb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-off" /></template>
<style>
.mx2lwm0ju {
  d: path("M8.6569 3L18 3C19.6569 3 21 4.3431 21 6L21 15.3431M20.1213 20.1213C19.5785 20.6642 18.8285 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 5.1715 3.3358 4.4215 3.8787 3.8787M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q7kx8tb-r {
  fill: currentColor;
  d: path("M16 7C16 7.5523 15.5523 8 15 8C14.4477 8 14 7.5523 14 7C14 6.4477 14.4477 6 15 6C15.5523 6 16 6.4477 16 7Z");
  stroke: none;
}

</style>
