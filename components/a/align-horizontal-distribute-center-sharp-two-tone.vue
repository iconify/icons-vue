<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lxh5bw8xz"/><path class="gk6wq0bfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-center-sharp-two-tone" /></template>
<style>
.gk6wq0bfx {
  d: path("M17 17H14V7H17M17 17H20V7H17M17 17V23M17 7V1M7 5H10V19H7M7 5H4V19H7M7 5V1M7 19V23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lxh5bw8xz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 4H10C10.552 4 11 4.448 11 5V19C11 19.552 10.552 20 10 20H8V23H6V20H4C3.448 20 3 19.552 3 19V5C3 4.448 3.448 4 4 4H6V1H8V4ZM18 6H20C20.552 6 21 6.448 21 7V17C21 17.552 20.552 18 20 18H18V23H16V18H14C13.448 18 13 17.552 13 17V7C13 6.448 13.448 6 14 6H16V1H18V6Z");
  stroke: none;
}

</style>
