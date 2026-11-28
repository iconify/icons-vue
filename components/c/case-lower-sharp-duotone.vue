<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s4_52vbkk"/><path class="ulpc5d51o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-lower-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s4_52vbkk {
  stroke-opacity: 0.4;
  d: path("M11 12.5C11 14.9853 8.9853 17 6.5 17C4.0147 17 2 14.9853 2 12.5C2 10.0147 4.0147 8 6.5 8C8.9853 8 11 10.0147 11 12.5ZM11 6V18");
}

.ulpc5d51o {
  d: path("M22 14C22 15.6569 20.6569 17 19 17C17.3431 17 16 15.6569 16 14C16 12.3431 17.3431 11 19 11C20.6569 11 22 12.3431 22 14ZM22 9V18");
}

</style>
