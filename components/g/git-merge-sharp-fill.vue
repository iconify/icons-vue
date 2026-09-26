<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zwmlwzbho"/><path class="g9tgbxrav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge-sharp-fill" /></template>
<style>
.g9tgbxrav {
  fill: currentColor;
  d: path("M6 14C3.9289 14 2 15.9289 2 18C2 20.0711 3.9289 22 6 22C8.0711 22 10 20.0711 10 18C10 15.9289 8.0711 14 6 14ZM18 2C15.9289 2 14 3.9289 14 6C14 8.0711 15.9289 10 18 10C20.0711 10 22 8.0711 22 6C22 3.9289 20.0711 2 18 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zwmlwzbho {
  d: path("M6 2L6 15C6.1667 12 8.2 6 15 6L16 6");
}

</style>
