<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pi2qqqb_t"/><path class="yk09w7pmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-dot-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi2qqqb_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 10C23 10.5523 22.5523 11 22 11L13 11L13 20C13 20.5523 12.5523 21 12 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.yk09w7pmf {
  d: path("M1.3954 6.7397L2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7L22.6046 6.7397M19 14C20.6568 14 22 15.3431 22 17C22 18.6568 20.6568 20 19 20C17.3432 20 16 18.6568 16 17C16 15.3431 17.3432 14 19 14Z");
}

</style>
