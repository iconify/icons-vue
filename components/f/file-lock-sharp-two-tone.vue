<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ty_s6ebnn"/><path class="lgbo8xc1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-lock-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lgbo8xc1p {
  d: path("M20 11L20 8L14 2L4 2L4 22L10 22M14 2L14 8L20 8M13 18L20 18L20 22L13 22ZM14.5 18L14.5 16C14.5 14.8954 15.3954 14 16.5 14C17.6046 14 18.5 14.8954 18.5 16L18.5 18");
}

.ty_s6ebnn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8L21 10C21 10.5523 20.5523 11 20 11L10 11L10 22C10 22.5523 9.5523 23 9 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
