<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b9-_bctro"/><path class="k0meeo2gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-badge-sharp-two-tone" /></template>
<style>
.b9-_bctro {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 1C19.5523 1 20 1.44772 20 2V22C20 22.5523 19.5523 23 19 23H5C4.44772 23 4 22.5523 4 22V2C4 1.44772 4.44772 1 5 1H19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k0meeo2gk {
  d: path("M5 2L19 2L19 22L5 22ZM9 6L10 6L14 6L15 6M14 13C14 14.1046 13.1046 15 12 15C10.8954 15 10 14.1046 10 13C10 11.8954 10.8954 11 12 11C13.1046 11 14 11.8954 14 13ZM8 22C8 20.3431 9.3432 19 11 19L13 19C14.6569 19 16 20.3431 16 22");
}

</style>
