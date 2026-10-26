<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-uzu-bnm"/><path class="y_l2mlzvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-uzu-bnm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 17C2.3431 17 1 15.6569 1 14L1 10C1 8.3431 2.3431 7 4 7L9.7639 7C11.0792 7 12.3764 6.6938 13.5528 6.1056C15.0069 5.3785 16.6104 5 18.2361 5L20 5C21.6569 5 23 6.3431 23 8L23 16C23 17.6569 21.6569 19 20 19L18.2361 19C16.6104 19 15.0069 18.6215 13.5528 17.8944C12.3764 17.3062 11.0792 17 9.7639 17L4 17Z");
  stroke: none;
}

.y_l2mlzvo {
  d: path("M12 12L10 12M17 7L17 17M4 16L9.7639 16C11.2344 16 12.6847 16.3424 14 17C15.3153 17.6576 16.7656 18 18.2361 18L20 18C21.1046 18 22 17.1046 22 16L22 8C22 6.8954 21.1046 6 20 6L18.2361 6C16.7656 6 15.3153 6.3424 14 7C12.6847 7.6576 11.2344 8 9.7639 8L4 8C2.8954 8 2 8.8954 2 10L2 14C2 15.1046 2.8954 16 4 16Z");
}

</style>
