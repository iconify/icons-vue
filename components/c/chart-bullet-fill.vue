<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="oy3_bdbpk"/><path class="olmipfbqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olmipfbqk {
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21M8 10L20 10C20.5523 10 21 10.4477 21 11L21 13C21 13.5523 20.5523 14 20 14L8 14C7.4477 14 7 13.5523 7 13L7 11C7 10.4477 7.4477 10 8 10ZM16 7V17");
}

.oy3_bdbpk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 9L8 9C6.8954 9 6 9.8954 6 11L6 13C6 14.1046 6.8954 15 8 15L16 15C16.5523 15 17 14.5523 17 14L17 10C17 9.4477 16.5523 9 16 9Z");
  stroke: none;
}

</style>
