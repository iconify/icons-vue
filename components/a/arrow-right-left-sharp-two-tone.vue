<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tfn7afb6l"/><path class="pdhbs_b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdhbs_b1m {
  d: path("M22 18L3 18M6.2929 14.7071L3 18L6.2929 21.2929");
}

.tfn7afb6l {
  stroke-opacity: 0.4;
  d: path("M2 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929");
}

</style>
