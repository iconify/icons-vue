<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k936e94hp"/><path class="zvmy9910g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-short-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k936e94hp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.7071 12.7071L11.7071 22.7071C11.4211 22.9931 10.991 23.0787 10.6173 22.9239C10.2436 22.7691 10 22.4045 10 22L10 18L3 18C2.4477 18 2 17.5523 2 17L2 7C2 6.4477 2.4477 6 3 6L10 6L10 2C10 1.5955 10.2436 1.2309 10.6173 1.0761C10.991 0.9213 11.4211 1.0069 11.7071 1.2929L21.7071 11.2929C22.0976 11.6834 22.0976 12.3166 21.7071 12.7071Z");
  stroke: none;
}

.zvmy9910g {
  d: path("M21 12L11 22L11 17L3 17L3 7L11 7L11 2Z");
}

</style>
