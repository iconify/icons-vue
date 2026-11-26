<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vuf0-cgwi"/><path class="xqvy6vb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d4-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vuf0-cgwi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.1268 11.5145L1.1278 20.5144C1.0453 20.663 1.002 20.8301 1.002 21C1.002 21.5523 1.4497 22 2.002 22L21.998 22C22.5503 22 22.998 21.5523 22.998 21C22.998 20.8301 22.9547 20.663 22.8722 20.5144L12.8742 2.5145C12.6978 2.197 12.3632 2.0001 12 2.0001C11.6368 2.0001 11.3022 2.197 11.1258 2.5145Z");
  stroke: none;
}

.xqvy6vb5s {
  d: path("M12 3.0001L2.002 21L21.998 21ZM12 3L12 14M3.0104 19.1834L12 14L20.9896 19.1834");
}

</style>
