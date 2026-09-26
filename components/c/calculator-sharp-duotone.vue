<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z_zygfbdd"/><path class="n2gzo9r6m"/><path class="wx6aefbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calculator-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n2gzo9r6m {
  d: path("M5 6L19 6M11 18L17 18");
}

.wx6aefbne {
  fill: currentColor;
  d: path("M9 10C9 10.5523 8.5523 11 8 11C7.4477 11 7 10.5523 7 10C7 9.4477 7.4477 9 8 9C8.5523 9 9 9.4477 9 10ZM13 10C13 10.5523 12.5523 11 12 11C11.4477 11 11 10.5523 11 10C11 9.4477 11.4477 9 12 9C12.5523 9 13 9.4477 13 10ZM17 10C17 10.5523 16.5523 11 16 11C15.4477 11 15 10.5523 15 10C15 9.4477 15.4477 9 16 9C16.5523 9 17 9.4477 17 10ZM9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM13 14C13 14.5523 12.5523 15 12 15C11.4477 15 11 14.5523 11 14C11 13.4477 11.4477 13 12 13C12.5523 13 13 13.4477 13 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14ZM9 18C9 18.5523 8.5523 19 8 19C7.4477 19 7 18.5523 7 18C7 17.4477 7.4477 17 8 17C8.5523 17 9 17.4477 9 18Z");
  stroke: none;
}

.z_zygfbdd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
