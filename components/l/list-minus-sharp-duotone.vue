<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="in4f_nj7p"/><path class="dyc7ambzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-minus-sharp-duotone" /></template>
<style>
.dyc7ambzy {
  d: path("M1 18L7 18M9 18L15 18M17 18L23 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.in4f_nj7p {
  stroke-opacity: 0.4;
  d: path("M1 6L23 6M1 12L23 12");
}

</style>
