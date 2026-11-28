<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mongioyea"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iframe-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mongioyea {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.7071 17.7071C17.5261 17.8881 17.2761 18 17 18L7 18C6.4477 18 6 17.5523 6 17L6 13C6 12.4477 6.4477 12 7 12L12 12ZM10 10L4 10L4 20L20 20L21.7071 21.7071C21.5262 21.8881 21.2762 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.7239 2.1119 2.4739 2.2929 2.2929ZM15.6569 12L17 12C17.5523 12 18 12.4477 18 13L18 14.3431ZM20 16.3431L20 10L13.6569 10L5.6569 2L12 2L21 2C21.5523 2 22 2.4477 22 3L22 18.3431Z");
  stroke: none;
}

</style>
