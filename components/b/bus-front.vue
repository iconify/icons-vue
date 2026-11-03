<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vecy8me2v"/><path clip-rule="evenodd" class="ll3q_q67o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-front" /></template>
<style>
.ll3q_q67o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vecy8me2v {
  d: path("M4 18L4 7C4 4.7909 5.7909 3 8 3L16 3C18.2091 3 20 4.7909 20 7L20 18ZM22 8L20 8L20 10L4 10L4 8L2 8M12 10L12 3M16 18L16 19.5C16 20.3284 16.6716 21 17.5 21L18.5 21C19.3284 21 20 20.3284 20 19.5L20 18M8 18L8 19.5C8 20.3284 7.3284 21 6.5 21L5.5 21C4.6716 21 4 20.3284 4 19.5L4 18");
}

</style>
