<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ffvfzwbbt"/><path class="hm8eiqb0z"/><path class="x_g3-9x6j"/><path class="r4_-znbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cupcake-sharp-duotone" /></template>
<style>
.ffvfzwbbt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.2193 15L3 15C2.4477 15 2 14.5523 2 14L2 13C2 10.2386 4.2386 8 7 8L17 8C19.7614 8 22 10.2386 22 13L22 14C22 14.5523 21.5523 15 21 15L19.7807 15L17.97 22.2425C17.8587 22.6877 17.4588 23 16.9999 23L7.0001 23C6.5412 23 6.1413 22.6877 6.03 22.2425Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hm8eiqb0z {
  fill: currentColor;
  d: path("M16.1328 13L19 13C19.5523 13 20 13.4477 20 14C20 14.0818 19.99 14.1632 19.9701 14.2425L17.97 22.2425C17.8587 22.6877 17.4588 23 16.9999 23L7.0001 23C6.5412 23 6.1413 22.6877 6.03 22.2425L4.0299 14.2425C4.01 14.1632 4 14.0818 4 14C4 13.4477 4.4477 13 5 13L7.8672 13L8.0077 14.124L8.8827 21.124L10.8673 20.876L9.9923 13.876L9.8828 13L12 13L14.1172 13L14.0077 13.876L13.1327 20.876L15.1173 21.124L15.9923 14.124Z");
  stroke: none;
}

.r4_-znbed {
  fill: currentColor;
  d: path("M13 2C13 2.5523 12.5523 3 12 3C11.4477 3 11 2.5523 11 2C11 1.4477 11.4477 1 12 1C12.5523 1 13 1.4477 13 2Z");
  stroke: none;
}

.x_g3-9x6j {
  d: path("M12 9L12 5");
}

</style>
