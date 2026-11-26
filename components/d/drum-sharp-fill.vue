<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="dutwohbup"/><path class="g3caaubki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drum-sharp-fill" /></template>
<style>
.dutwohbup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.988 10.0001C4.992 10 4.996 10 5 10L12 10L19 10C19.004 10 19.008 10 19.012 10.0001L21 10.0001L22 10.0001L22 12.0001L21 12.0001L20 12.0001L20 20.0001L22 20.0001L22 22.0001L2 22.0001L2 20.0001L4 20.0001L4 16L4 12.0001L3 12.0001L2 12.0001L2 10.0001L3 10.0001ZM11 12L11 20L13 20L13 12Z");
  stroke: none;
}

.g3caaubki {
  d: path("M3.7071 2.7071L4 3L8 7L8.2929 7.2929M20.2929 2.7071L20 3L16 7L15.7071 7.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
