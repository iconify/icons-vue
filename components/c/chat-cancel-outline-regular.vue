<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="k98hrmbbs"/><path class="cc3qf6bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-cancel-outline-regular" /></template>
<style>
.cc3qf6bsy {
  d: path("m14.5 8 -5 5");
}

.hbdbg_bcy {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.k98hrmbbs {
  d: path("m9.5 8 5 5");
}

.lyjarcbwz {
  d: path("M7 18v3l3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
