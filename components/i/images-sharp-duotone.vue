<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xtbju33sf"/><path class="z308c8bnb"/><path clip-rule="evenodd" class="l795ftb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l795ftb_f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 13.5L14.5528 10.2237C14.8343 10.0829 15.1657 10.0829 15.4472 10.2237L20 12.5L20 15C20 15.5523 19.5523 16 19 16L9 16C8.4477 16 8 15.5523 8 15L8 13.5ZM12 7C12 7.5523 11.5523 8 11 8C10.4477 8 10 7.5523 10 7C10 6.4477 10.4477 6 11 6C11.5523 6 12 6.4477 12 7Z");
  stroke: none;
}

.xtbju33sf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L7 18C6.4477 18 6 17.5523 6 17L6 3C6 2.4477 6.4477 2 7 2Z");
  stroke: none;
}

.z308c8bnb {
  stroke-opacity: 0.4;
  d: path("M3 7L3 21L17 21");
}

</style>
