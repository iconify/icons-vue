<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hskg5cwll"/><path class="dae_7s_yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-arrow-up-sharp-two-tone" /></template>
<style>
.dae_7s_yq {
  d: path("M11 20L3 20L3 4L9.5 4L12 6.5L21 6.5L21 11M18 21L18 14M14.7071 17.2929L18 14L21.2929 17.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hskg5cwll {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3L9.5 3C9.7652 3 10.0196 3.1054 10.2071 3.2929L12.4144 5.5L21 5.5C21.5523 5.5 22 5.9477 22 6.5L22 10C22 10.5523 21.5523 11 21 11L11 11L11 20C11 20.5523 10.5523 21 10 21L3 21C2.4477 21 2 20.5523 2 20L2 4C2 3.4477 2.4477 3 3 3Z");
  stroke: none;
}

</style>
