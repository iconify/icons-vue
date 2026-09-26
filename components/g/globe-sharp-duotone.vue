<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v80--9b_b"/><path class="vzahb9b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v80--9b_b {
  stroke-opacity: 0.4;
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12Z");
}

.vzahb9b9j {
  d: path("M2 12L22 12M12 2C14.6667 5 16 8.5 16 12C16 15.5 14.6667 19 12 22C9.3333 19 8 15.5 8 12C8 8.5 9.3333 5 12 2Z");
}

</style>
