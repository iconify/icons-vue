<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cx2a49bhn"/><path class="u8qhtt3pv"/><path class="qxw3kzbst"/><path class="f-6g2x7la"/><path class="wwmhxmb7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-line-duotone" /></template>
<style>
.cx2a49bhn {
  d: path("M14 15H10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f-6g2x7la {
  d: path("M6.99982 2H8.73347C9.83804 2 9.99982 2.89543 9.99982 4V20C9.99982 21.1046 9.10439 22 7.99982 22H3.99982C2.89525 22 1.99982 21.1046 1.99982 20C1.99982 20 1.84202 16.9462 1.99982 15C2.35967 10.5619 4.76936 5.22135 4.99982 4C5.23028 2.77865 5.49982 2 6.99982 2Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qxw3kzbst {
  d: path("M14 9H10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u8qhtt3pv {
  d: path("M9.99977 19H1.96045M22.0397 19H13.9943");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wwmhxmb7s {
  d: path("M17.0002 2H15.2665C14.162 2 14.0002 2.89543 14.0002 4V20C14.0002 21.1046 14.8956 22 16.0002 22H20.0002C21.1047 22 22.0002 21.1046 22.0002 20C22.0002 20 22.158 16.9462 22.0002 15C21.6403 10.5619 19.2306 5.22135 19.0002 4C18.7697 2.77865 18.5002 2 17.0002 2Z");
}

</style>
