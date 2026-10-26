<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6er8mbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-sharp" /></template>
<style>
.b6er8mbij {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10L21 10L21 20L17.5 20L17 18L7 18L6.5 20L3 20ZM5.0513 10L5.35177 9L7.5 4L16.5 4L18.6482 9L18.9487 10M5.35177 9L2.5 9M18.6482 9L21.5 9M8 12.5L8 15.5M16 12.5L16 15.5");
}

</style>
