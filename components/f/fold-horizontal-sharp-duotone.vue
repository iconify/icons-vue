<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y_27l763x"/><path class="vffx6t6bn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fold-horizontal-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vffx6t6bn {
  d: path("M1 12L8 12M4.7071 8.7071L8 12L4.7071 15.2929M23 12L16 12M19.2929 8.7071L16 12L19.2929 15.2929");
}

.y_27l763x {
  stroke-opacity: 0.4;
  d: path("M12 4L12 20");
}

</style>
