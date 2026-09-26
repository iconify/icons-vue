<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w5c8y-14a"/><path class="z7exlgodl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-arrow-right-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w5c8y-14a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.707 1.293L20.7071 7.2929C20.8946 7.4805 21 7.7348 21 8.0001L21 12C21 12.5523 20.5523 13 20 13L11 13L11 22C11 22.5523 10.5523 23 10 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1L14 1C14.2652 1 14.5195 1.1054 14.707 1.293Z");
  stroke: none;
}

.z7exlgodl {
  d: path("M14 2L4 2L4 22L11 22M14 2L20 8L20 13M14 2L14 8L20 8M13 19L20 19M16.7071 15.7071L20 19L16.7071 22.2929");
}

</style>
