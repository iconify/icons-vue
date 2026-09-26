<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="uefyiehrl"/><path class="ah9s1bcom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:contacts-sharp-fill" /></template>
<style>
.ah9s1bcom {
  d: path("M4 3L20 3");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uefyiehrl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 6L21 6C21.5523 6 22 6.4477 22 7L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 7C2 6.4477 2.4477 6 3 6ZM15 13C15 11.3431 13.6569 10 12 10C10.3431 10 9 11.3431 9 13C9 14.6569 10.3431 16 12 16C13.6569 16 15 14.6569 15 13ZM7 20L17 20L17 18L7 18L7 20Z");
  stroke: none;
}

</style>
