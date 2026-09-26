<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w022pybkb"/><path class="y41ihub8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-closed-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w022pybkb {
  d: path("M6 22L6 8M18 10.5L18 16M15.2071 2.7071L20.7929 8.2929M20.7929 2.7071L15.2071 8.2929");
}

.y41ihub8g {
  fill: currentColor;
  d: path("M6 2C8.0711 2 10 3.9289 10 6C10 8.0711 8.0711 10 6 10C3.9289 10 2 8.0711 2 6C2 3.9289 3.9289 2 6 2ZM18 14C20.0711 14 22 15.9289 22 18C22 20.0711 20.0711 22 18 22C15.9289 22 14 20.0711 14 18C14 15.9289 15.9289 14 18 14Z");
  stroke: none;
}

</style>
