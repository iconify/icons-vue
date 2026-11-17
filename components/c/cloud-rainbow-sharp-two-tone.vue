<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rc_m_6bnn"/><path class="cfejl4kac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rainbow-sharp-two-tone" /></template>
<style>
.cfejl4kac {
  d: path("M6.033 8.93L6.215 8.16C7.068 4.55 10.291 2 14 2C18.418 2 22 5.582 22 10V16M10.501 7.998L10.801 7.598C11.557 6.592 12.742 6 14 6C16.209 6 18 7.791 18 10V14.2M14 22H5C3.343 22 2 20.657 2 19C2 17.343 3.343 16 5 16C5 13.515 7.015 11.5 9.5 11.5C11.985 11.5 14 13.515 14 16C15.657 16 17 17.343 17 19C17 20.657 15.657 22 14 22Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rc_m_6bnn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 19C18 21.209 16.209 23 14 23H5C2.791 23 1 21.209 1 19C1 17.11 2.31 15.527 4.072 15.108C4.498 12.495 6.766 10.5 9.5 10.5C12.234 10.5 14.501 12.495 14.927 15.108C16.689 15.526 18 17.11 18 19Z");
  stroke: none;
}

</style>
