<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="iv8f1fb4p"/><path class="tlk6yobhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-horizontal-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iv8f1fb4p {
  stroke-opacity: 0.4;
  d: path("M2 6L10 6M6.7071 2.7071L10 6L6.7071 9.2929M22 6L14 6M17.2929 2.7071L14 6L17.2929 9.2929");
}

.tlk6yobhf {
  d: path("M6 12L6 22M12 12L12 22M18 12L18 22");
}

</style>
