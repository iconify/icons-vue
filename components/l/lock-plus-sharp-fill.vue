<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w3aaq-w9x"/><path clip-rule="evenodd" class="rl6vxcocx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-plus-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rl6vxcocx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 10C3 9.4477 3.4477 9 4 9L20 9C20.5523 9 21 9.4477 21 10L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22ZM13 17L15 17L15 15L13 15L13 13L11 13L11 15L9 15L9 17L11 17L11 19L13 19Z");
  stroke: none;
}

.w3aaq-w9x {
  d: path("M7.5 11L7.5 6.5C7.5 4.0147 9.5147 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 11");
}

</style>
