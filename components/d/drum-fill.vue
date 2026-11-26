<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="a4on43bjp"/><path class="sv3-ubbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drum-fill" /></template>
<style>
.a4on43bjp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.988 10.0001C4.992 10 4.996 10 5 10L12 10L19 10C19.004 10 19.008 10 19.012 10.0001L21 10.0001C21.5523 10.0001 22 10.4478 22 11.0001C22 11.5524 21.5523 12.0001 21 12.0001L20 12.0001L20 20.0001L21 20.0001C21.5523 20.0001 22 20.4478 22 21.0001C22 21.5524 21.5523 22.0001 21 22.0001L3 22.0001C2.4477 22.0001 2 21.5524 2 21.0001C2 20.4478 2.4477 20.0001 3 20.0001L4 20.0001L4 16L4 12.0001L3 12.0001C2.4477 12.0001 2 11.5524 2 11.0001C2 10.4478 2.4477 10.0001 3 10.0001ZM11 12L11 20L13 20L13 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sv3-ubbul {
  d: path("M4 3L8 7M20 3L16 7");
}

</style>
