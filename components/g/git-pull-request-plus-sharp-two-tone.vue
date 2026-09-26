<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="khsra6f7m"/><path class="dfyd-dbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-plus-sharp-two-tone" /></template>
<style>
.dfyd-dbyd {
  d: path("M6 15L6 2M18 14L18 22M14 18L22 18M18 12L18 9M9 18L12 18M6 15C7.6569 15 9 16.3431 9 18C9 19.6569 7.6569 21 6 21C4.3431 21 3 19.6569 3 18C3 16.3431 4.3431 15 6 15ZM18 3C19.6569 3 21 4.3431 21 6C21 7.6569 19.6569 9 18 9C16.3431 9 15 7.6569 15 6C15 4.3431 16.3431 3 18 3Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.khsra6f7m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 14C8.0711 14 10 15.9289 10 18C10 20.0711 8.0711 22 6 22C3.9289 22 2 20.0711 2 18C2 15.9289 3.9289 14 6 14ZM18 2C20.0711 2 22 3.9289 22 6C22 8.0711 20.0711 10 18 10C15.9289 10 14 8.0711 14 6C14 3.9289 15.9289 2 18 2Z");
  stroke: none;
}

</style>
