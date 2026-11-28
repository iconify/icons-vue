<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d08n8c6cs"/><path clip-rule="evenodd" class="l599izq9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gearbox-sharp-duotone" /></template>
<style>
.d08n8c6cs {
  stroke-opacity: 0.4;
  d: path("M4 1V23M20 1V23M12 8V23M4 12H20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l599izq9v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.828 7.828C14.106 8.551 13.104 9 12 9C9.791 9 8 7.209 8 5C8 2.791 9.791 1 12 1C14.209 1 16 2.791 16 5C16 6.104 15.551 7.106 14.828 7.828Z");
  stroke: none;
}

</style>
