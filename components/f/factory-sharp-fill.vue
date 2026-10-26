<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="duufhimxh"/><path class="mq9-n5wuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:factory-sharp-fill" /></template>
<style>
.duufhimxh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 21L1 3C1 2.4477 1.4477 2 2 2L7 2C7.5523 2 8 2.4477 8 3L8 9.2338L11.4855 7.1425C11.6409 7.0493 11.8188 7 12 7C12.5523 7 13 7.4477 13 8L13 9.2338L16.4855 7.1425C16.6409 7.0493 16.8188 7 17 7C17.5523 7 18 7.4477 18 8L18 9.2338L21.4855 7.1425C21.6409 7.0493 21.8188 7 22 7C22.5523 7 23 7.4477 23 8L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21ZM11 14L9 14L9 18L11 18L11 14ZM15 14L13 14L13 18L15 18L15 14ZM19 14L17 14L17 18L19 18L19 14ZM3 6L3 8L6 8L6 6L3 6Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mq9-n5wuo {
  d: path("M11 5.5L11 3L23 3");
}

</style>
