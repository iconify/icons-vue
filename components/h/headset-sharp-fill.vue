<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l4l2bivlj"/><path class="fuzt8obdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-sharp-fill" /></template>
<style>
.fuzt8obdb {
  d: path("M4 11L4 10C4 5.5817 7.5817 2 12 2C16.4183 2 20 5.5817 20 10L20 11M18 17L18 22L11 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l4l2bivlj {
  fill: currentColor;
  d: path("M3 10C3 8.4812 4.4812 7 6 7L8 7C8.5523 7 9 7.4477 9 8L9 18C9 18.5523 8.5523 19 8 19L6 19C4.4812 19 3 17.5188 3 16L3 10ZM21 10C21 8.4812 19.5188 7 18 7L16 7C15.4477 7 15 7.4477 15 8L15 18C15 18.5523 15.4477 19 16 19L18 19C19.5188 19 21 17.5188 21 16L21 10Z");
  stroke: none;
}

</style>
