<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bz8a_bbev"/><path class="mjctudrqh"/><path class="klc39u_3r"/><path class="w2k_i3yyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-scan-sharp-duotone" /></template>
<style>
.bz8a_bbev {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12V21C14 21.5523 13.5523 22 13 22H3C2.4477 22 2 21.5523 2 21V3C2 2.4477 2.4477 2 3 2H13C13.5523 2 14 2.4477 14 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.klc39u_3r {
  d: path("M13 1V23");
}

.mjctudrqh {
  fill: currentColor;
  d: path("M4 6.5H7V8.5H4ZM4 11H7V13H4ZM4 15.5H7V17.5H4ZM9 4H13V11H9ZM9 13H13V20H9Z");
  stroke: none;
}

.w2k_i3yyo {
  stroke-opacity: 0.4;
  d: path("M17 2V11M17 22V13M21 21V17M21 15V9M21 7V3");
}

</style>
