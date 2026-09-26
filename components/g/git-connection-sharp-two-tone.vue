<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f25gi5bye"/><path class="groubrorl"/><path class="ft5hym8ya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection-sharp-two-tone" /></template>
<style>
.f25gi5bye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 14C15.9289 14 14 15.9289 14 18C14 20.0711 15.9289 22 18 22C20.0711 22 22 20.0711 22 18C22 15.9289 20.0711 14 18 14ZM3 2L9 2C9.5523 2 10 2.4477 10 3L10 9C10 9.5523 9.5523 10 9 10L3 10C2.4477 10 2 9.5523 2 9L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.ft5hym8ya {
  d: path("M18 15C19.6569 15 21 16.3431 21 18C21 19.6569 19.6569 21 18 21C16.3431 21 15 19.6569 15 18C15 16.3431 16.3431 15 18 15ZM3 3L9 3L9 9L3 9L3 3Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.groubrorl {
  d: path("M6 9L6 18L12 18M12 6L18 6L18 15");
}

</style>
