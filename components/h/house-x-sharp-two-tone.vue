<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i1obncyts"/><path class="iiyqsnb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-x-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i1obncyts {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3857 3.20703C11.7469 2.92599 12.253 2.92599 12.6142 3.20703L13 3.50684V11H21V22C20.9999 22.5522 20.5522 23 20 23H3.99996C3.44776 23 3.00007 22.5522 2.99996 22V12.2666L2.22848 12.8672L0.999962 11.2891L11.3857 3.20703Z");
  stroke: none;
}

.iiyqsnb3t {
  d: path("M1.6141 12.0785L2 11.7782L12 3.9963L12.3859 4.2966M4 10.2218L4 22L20 22L20 12L20 11M9 22L9 19C9 17.3431 10.3431 16 12 16C13.6569 16 15 17.3431 15 19L15 22M15.7071 1.7071L16 2L22 8L22.2929 8.2929M22.2929 1.7071L22 2L16 8L15.7071 8.2929");
}

</style>
