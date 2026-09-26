<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xdh9roo8a"/><path class="rlvkt7p5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlvkt7p5j {
  d: path("M14.929 3L22 10.071L11.0711 21L7.071 21L2 15.929L14.929 3ZM8 9.9289L15.0711 17M9.071 21L23 21");
}

.xdh9roo8a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.4853 20L23 20L23 22L7.071 22C6.8058 22 6.5514 21.8946 6.3639 21.7071L1.2928 16.6361C1.1053 16.4486 1 16.1942 1 15.929C1 15.6638 1.1053 15.4094 1.2928 15.2219L14.2219 2.2928C14.4094 2.1053 14.6638 2 14.929 2C15.1942 2 15.4486 2.1053 15.6361 2.2928L22.7072 9.3639C22.8947 9.5514 23 9.8058 23 10.071C23 10.3362 22.8947 10.5906 22.7072 10.7781L13.4853 20Z");
  stroke: none;
}

</style>
