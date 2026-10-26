<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="iu59hf0tf"/><path class="jpr9rputn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iu59hf0tf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 17C1.4477 17 1 16.5523 1 16L1 8C1 7.4477 1.4477 7 2 7L9.7639 7C11.0792 7 12.3764 6.6938 13.5528 6.1056C15.0069 5.3785 16.6103 5 18.2361 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23 18.5523 22.5523 19 22 19L18.2361 19C16.6104 19 15.0069 18.6215 13.5528 17.8944C12.3764 17.3063 11.0792 17 9.7639 17L2 17Z");
  stroke: none;
}

.jpr9rputn {
  d: path("M9 12L13 12M17 7L17 17M2 16L9.76393 16C11.2344 16 12.6847 16.3424 14 17C15.3153 17.6576 16.7656 18 18.2361 18L22 18L22 6L18.2361 6C16.7656 6 15.3153 6.34237 14 7C12.6847 7.65763 11.2344 8 9.76393 8L2 8Z");
}

</style>
