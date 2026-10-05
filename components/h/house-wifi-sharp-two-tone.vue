<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sth-sfoin"/><path class="yalroebyj"/><path class="f4ihe5fmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-wifi-sharp-two-tone" /></template>
<style>
.f4ihe5fmy {
  fill: currentColor;
  d: path("M13 21C13 21.5523 12.5523 22 12 22C11.4477 22 11 21.5523 11 21C11 20.4477 11.4477 20 12 20C12.5523 20 13 20.4477 13 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sth-sfoin {
  stroke-opacity: 0.4;
  d: path("M1.6141 11.0785L2 10.7782L12 2.9963L22 10.7782L22.3859 11.0785M4 9.2218L4 21L8 21L9 21M15 21L16 21L20 21L20 9.2218");
}

.yalroebyj {
  d: path("M9.5 17.8246L10 17.5359C10.6081 17.1848 11.2979 17 12 17C12.7021 17 13.3919 17.1848 14 17.5359L14.5 17.8246M7.5 14.3605L8 14.0718C9.2162 13.3697 10.5957 13 12 13C13.4043 13 14.7838 13.3697 16 14.0718L16.5 14.3605");
}

</style>
