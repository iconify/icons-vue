<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mr239ib0b"/><path class="nm633saev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broom-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mr239ib0b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.5304 13.5362C10.1768 14.466 6.5597 16.1295 2.9198 15.3456C5.7967 18.8355 12.1346 24.7603 14.4719 20.5399C15.086 19.4704 16.2577 17.1141 16.0316 16.2453ZM11.5304 13.5362C11.9756 12.2895 13.4622 10.069 15.8469 11.1603C17.9275 12.3742 16.8369 15.0561 16.0316 16.2453Z");
  stroke: none;
}

.nm633saev {
  d: path("M11.5304 13.5362C10.1768 14.466 6.5597 16.1295 2.9198 15.3456C5.7967 18.8355 12.1346 24.7603 14.4719 20.5399C15.086 19.4704 16.2577 17.1141 16.0316 16.2453ZM11.5304 13.5362C11.9756 12.2895 13.4622 10.069 15.8469 11.1603M16.0316 16.2453C16.8369 15.0561 17.9275 12.3742 15.8469 11.1603M15.8469 11.1603L21.2053 1.4845");
}

</style>
