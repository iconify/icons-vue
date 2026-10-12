<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oireozd_x"/><path class="urigu4bfy"/><path clip-rule="evenodd" class="clzhx63lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-simple-sharp-duotone" /></template>
<style>
.clzhx63lw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5ZM10.5 14.5C10.5 15.3284 9.8284 16 9 16C8.1716 16 7.5 15.3284 7.5 14.5C7.5 13.6716 8.1716 13 9 13C9.8284 13 10.5 13.6716 10.5 14.5ZM16.5 14.5C16.5 15.3284 15.8284 16 15 16C14.1716 16 13.5 15.3284 13.5 14.5C13.5 13.6716 14.1716 13 15 13C15.8284 13 16.5 13.6716 16.5 14.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oireozd_x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7L20 7C20.5523 7 21 7.4477 21 8L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 8C3 7.4477 3.4477 7 4 7Z");
  stroke: none;
}

.urigu4bfy {
  d: path("M12 8L12 3.5");
}

</style>
