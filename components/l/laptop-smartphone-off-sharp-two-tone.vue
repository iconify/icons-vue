<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r497xz1cb"/><path class="rvx1t9w9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r497xz1cb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.293 22.293L21.586 23H13C12.448 23 12 22.552 12 22V12L22.293 22.293ZM12.702 9.045C12.796 9.016 12.896 9 13 9H22C22.552 9 23 9.448 23 10V19.343L12.702 9.045ZM6.657 1H7.657H20C20.552 1 21 1.448 21 2V5H19V3H7.657H6.657V1Z");
  stroke: none;
}

.rvx1t9w9i {
  d: path("M4 14V4M10 18H2V14H10M13 13V22H22M1.707 1.707L22.293 22.293");
}

</style>
