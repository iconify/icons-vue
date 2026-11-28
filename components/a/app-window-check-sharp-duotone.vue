<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yftakub3m"/><path class="dwl9f-97b"/><path clip-rule="evenodd" class="ap0levf8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-check-sharp-duotone" /></template>
<style>
.ap0levf8n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7C8 7.5523 7.552 8 7 8C6.448 8 6 7.5523 6 7C6 6.4477 6.448 6 7 6C7.552 6 8 6.4477 8 7ZM12 7C12 7.5523 11.552 8 11 8C10.448 8 10 7.5523 10 7C10 6.4477 10.448 6 11 6C11.552 6 12 6.4477 12 7ZM16 7C16 7.5523 15.552 8 15 8C14.448 8 14 7.5523 14 7C14 6.4477 14.448 6 15 6C15.552 6 16 6.4477 16 7Z");
  stroke: none;
}

.dwl9f-97b {
  d: path("M14.707 17.7071L17 20L21.293 15.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yftakub3m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2H21C21.552 2 22 2.4477 22 3V11C22 11.5523 21.552 12 21 12H12V21C12 21.5523 11.552 22 11 22H3C2.448 22 2 21.5523 2 21V3C2 2.4477 2.448 2 3 2Z");
  stroke: none;
}

</style>
