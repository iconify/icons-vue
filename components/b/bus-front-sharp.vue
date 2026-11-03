<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j5rfucc4p"/><path clip-rule="evenodd" class="ll3q_q67o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-front-sharp" /></template>
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

.ll3q_q67o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14Z");
  stroke: none;
}

</style>
