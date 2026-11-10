<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bmxt8b0vu"/><path class="vsnrjqbwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-sharp-two-tone" /></template>
<style>
.bmxt8b0vu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 6C21.552 6 22 6.45 22 7V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V7C2 6.45 2.448 6 3 6H21ZM20 4H4V2H20V4Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vsnrjqbwe {
  d: path("M4 3H20M3 7H21V21H3V7ZM9.5 10.38L14.813 14L9.5 17.62V10.38Z");
}

</style>
