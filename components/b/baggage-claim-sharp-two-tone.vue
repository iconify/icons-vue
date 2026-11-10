<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g7q67ybvp"/><path class="usuo-lk-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baggage-claim-sharp-two-tone" /></template>
<style>
.g7q67ybvp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 3.057C17.5 3.554 21 7.367 21 12V16H23V18H20.231C20.708 18.531 21 19.231 21 20C21 21.657 19.657 23 18 23C16.343 23 15 21.657 15 20C15 19.231 15.292 18.531 15.769 18H8.231C8.708 18.531 9 19.231 9 20C9 21.657 7.657 23 6 23C4.343 23 3 21.657 3 20C3 19.231 3.292 18.531 3.769 18H1V16H3V12C3 7.367 6.5 3.554 11 3.057V1H13V3.057Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.usuo-lk-f {
  d: path("M1 17H23M4 17V12C4 7.582 7.582 4 12 4M12 4C16.418 4 20 7.582 20 12V17M12 4V1M8 17V12H10M10 12V8H14V12M10 12H14M14 12H16V17M18 22C16.895 22 16 21.105 16 20C16 18.895 16.895 18 18 18C19.105 18 20 18.895 20 20C20 21.105 19.105 22 18 22ZM6 22C4.895 22 4 21.105 4 20C4 18.895 4.895 18 6 18C7.105 18 8 18.895 8 20C8 21.105 7.105 22 6 22Z");
}

</style>
