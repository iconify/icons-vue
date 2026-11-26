<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sqa284bre"/><path class="u02wj3bbg"/><path class="s2sjb_7wh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:jacket-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s2sjb_7wh {
  d: path("M7 9L7 19M17 9L17 19");
}

.sqa284bre {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.4811 11.0113L22.9802 18.8113C22.9922 18.8735 22.9982 18.9367 22.9982 19C22.9982 19.5523 22.5505 20 21.9982 20L18 20L18 22C18 22.5523 17.5523 23 17 23L7 23C6.4477 23 6 22.5523 6 22L6 20L2.0019 20C1.4496 20 1.0019 19.5523 1.0019 19C1.0019 18.9367 1.0079 18.8735 1.0199 18.8113L4.018 3.2114C4.0845 2.8652 4.3284 2.5796 4.6599 2.4597L8.5284 1.0605C8.6374 1.0211 8.7525 1.0009 8.8685 1.0009C9.2628 1.0009 9.6203 1.2326 9.7813 1.5925L12 6.5514L14.2187 1.5925C14.3797 1.2326 14.7372 1.0009 15.1315 1.0009C15.2475 1.0009 15.3626 1.0211 15.4716 1.0605L19.3401 2.4597C19.6716 2.5796 19.9155 2.8652 19.982 3.2114Z");
  stroke: none;
}

.u02wj3bbg {
  fill: currentColor;
  d: path("M11 23L11 22L11 8.9999L11 5.9999L11.7532 5.9999L12 6.5514L12.2468 5.9999L13 5.9999L13 8.9999L13 22L13 23Z");
  stroke: none;
}

</style>
