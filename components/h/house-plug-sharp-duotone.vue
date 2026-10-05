<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qqmw-mbrm"/><path class="dva3llbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-plug-sharp-duotone" /></template>
<style>
.dva3llbez {
  d: path("M10 9L10 12M14 9L14 12M8 12L16 12L16 13C16 15.2091 14.2091 17 12 17C9.7909 17 8 15.2091 8 13ZM12 17L12 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qqmw-mbrm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3857 2.20711C11.7469 1.92603 12.253 1.92603 12.6142 2.20711L23 10.2891L21.7714 11.8673L21 11.2667V21.0001C20.9999 21.5523 20.5522 22.0001 20 22.0001H3.99996C3.44776 22.0001 3.00007 21.5523 2.99996 21.0001V11.2667L2.22848 11.8673L0.999962 10.2891L11.3857 2.20711Z");
  stroke: none;
}

</style>
