<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okhy_ybad"/><path class="prqt92bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okhy_ybad {
  stroke-opacity: 0.4;
  d: path("M2 18.001L3.7857 13.001L6.0583 6.668C6.3743 5.783 7.6257 5.783 7.9417 6.668L10.2143 13.001L12 18.001M10.2143 13.001H3.7857");
}

.prqt92bux {
  d: path("M22 15.001C22 16.658 20.6569 18.001 19 18.001C17.3431 18.001 16 16.658 16 15.001C16 13.344 17.3431 12.001 19 12.001C20.6569 12.001 22 13.344 22 15.001ZM22 15.001V11.001M22 15.001V18.001");
}

</style>
