<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tdujq9r_o"/><path clip-rule="evenodd" class="lfjv2ac0j"/><path class="b_nbonb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caravan-sharp-duotone" /></template>
<style>
.b_nbonb-s {
  d: path("M10 18C10 19.1046 9.1046 20 8 20C6.8954 20 6 19.1046 6 18C6 16.8954 6.8954 16 8 16C9.1046 16 10 16.8954 10 18Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lfjv2ac0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 7L6 7C6.5523 7 7 7.4477 7 8L7 12C7 12.5523 6.5523 13 6 13L3 13L3 7ZM9 13.1L9 8C9 7.4477 9.4477 7 10 7L15 7C15.5523 7 16 7.4477 16 8L16 17L12.9 17C12.4979 15.0365 10.9635 13.5021 9 13.1Z");
  stroke: none;
}

.tdujq9r_o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 15L20 18C20 18.5523 19.5523 19 19 19L2 19C1.4477 19 1 18.5523 1 18L1 4C1 3.4477 1.4477 3 2 3L19 3C19.5523 3 20 3.4477 20 4L20 13L23 13L23 15L20 15Z");
  stroke: none;
}

</style>
