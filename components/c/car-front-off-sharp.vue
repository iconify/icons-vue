<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax9m510vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-off-sharp" /></template>
<style>
.ax9m510vq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20L17.5 20L17 18L7 18L6.5 20L3 20L3 10L10 10M5.0513 10L5.3518 9L6.4482 6.4482M5.3518 9L2.5 9M8 12.5L8 15.5M14.6569 10L21 10L21 16.3431M8.6569 4L16.5 4L18.6482 9L18.9487 10M18.6482 9L21.5 9M1.7071 1.7071L22.2929 22.2929");
}

</style>
