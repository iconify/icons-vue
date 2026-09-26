<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="voakxho5e"/><path class="tg0xmb4fk"/><path class="cna37lbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-music-sharp-duotone" /></template>
<style>
.cna37lbtr {
  d: path("M22 15L22 5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tg0xmb4fk {
  fill: currentColor;
  d: path("M23 15C23 17.0711 21.0711 19 19 19C16.9289 19 15 17.0711 15 15C15 12.9289 16.9289 11 19 11C21.0711 11 23 12.9289 23 15Z");
  stroke: none;
}

.voakxho5e {
  stroke-opacity: 0.4;
  d: path("M1 6L17 6M1 12L11 12M1 18L11 18");
}

</style>
