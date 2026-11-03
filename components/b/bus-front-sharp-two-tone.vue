<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="khwbjh1sp"/><path class="j5rfucc4p"/><path clip-rule="evenodd" class="ll3q_q67o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-front-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j5rfucc4p {
  d: path("M4 18L4 3L20 3L20 18L4 18ZM23 8L20 8L20 10L4 10L4 8L1 8M12 10L12 3M16 18L16 21L20 21L20 18M8 18L8 21L4 21L4 18");
}

.khwbjh1sp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 19L9 19L9 21C9 21.5523 8.5523 22 8 22L4 22C3.4477 22 3 21.5523 3 21L3 9.0001L1 9.0001L1 7.0001L3 7.0001L3 3C3 2.4477 3.4477 2 4 2L20 2C20.5523 2 21 2.4477 21 3L21 7.0001L23 7.0001L23 9.0001L21 9.0001L21 10.0001C21 10.0027 21 10.0053 21 10.0079L21 21C21 21.5523 20.5523 22 20 22L16 22C15.4477 22 15 21.5523 15 21L15 19Z");
  stroke: none;
}

.ll3q_q67o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14Z");
  stroke: none;
}

</style>
