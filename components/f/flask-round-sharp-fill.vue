<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pt7ncdbcc"/><path class="dx93_50hj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-round-sharp-fill" /></template>
<style>
.dx93_50hj {
  d: path("M7 2L17 2");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt7ncdbcc {
  fill: currentColor;
  d: path("M9.5 1L14.5 1C15.0523 1 15.5 1.4477 15.5 2L15.5 7.8063C18.2529 9.1456 20 11.9386 20 15C20 19.4183 16.4183 23 12 23C7.5817 23 4 19.4183 4 15C4 11.9386 5.7471 9.1456 8.5 7.8063L8.5 2C8.5 1.4477 8.9477 1 9.5 1ZM10.5 3L10.5 8.4617C10.5 8.8761 10.2443 9.2477 9.8571 9.3957C7.5342 10.2839 6 12.5131 6 15L18 15C18 12.5131 16.4658 10.2839 14.1429 9.3957C13.7557 9.2477 13.5 8.8761 13.5 8.4617L13.5 3L10.5 3Z");
  stroke: none;
}

</style>
