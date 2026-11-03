<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="aa7wsqbsn"/><path class="pf-qlpbfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight-off-sharp-two-tone" /></template>
<style>
.aa7wsqbsn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M19 19L18.2361 19C16.6103 19 15.0069 18.6215 13.5528 17.8944C12.3764 17.3062 11.0792 17 9.7639 17L2 17C1.4477 17 1 16.5523 1 16L1 8C1 7.4477 1.4477 7 2 7L7 7L19 19ZM10.6917 6.9491C11.6878 6.8393 12.6565 6.5538 13.5528 6.1056C15.0069 5.3785 16.6103 5 18.2361 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23.0002 18.3293 22.8381 18.6376 22.5667 18.8241L10.6917 6.9491Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pf-qlpbfr {
  d: path("M9 12L12 12M8 8L2 8L2 16L9.7639 16C11.2344 16 12.6847 16.3424 14 17C15.2439 17.6219 16.6086 17.9619 17.997 17.997M1.7071 1.7071L22.2929 22.2929");
}

</style>
