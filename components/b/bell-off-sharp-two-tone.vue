<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vae5mmbzb"/><path class="pcksan_cu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pcksan_cu {
  d: path("M16 16H5V15C5 14 7 13 7 8C7 7.687 7.0288 7.3808 7.0838 7.0838M9.7679 19.134C10.6252 20.6188 11.2855 21 12 21C12.7145 21 13.3748 20.6188 14.2321 19.134M1.7071 1.7071L22.2929 22.2929");
}

.vae5mmbzb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 17H5C4.4477 17 4 16.5523 4 16V15C4 14.4387 4.2784 13.9674 4.455 13.673C4.6689 13.3166 4.8785 13.007 5.1056 12.5528C5.5331 11.6977 6 10.3517 6 8C6 7.3938 6.0899 6.8086 6.2571 6.2571L17 17ZM7.6444 3.98C8.7603 2.7795 10.3317 2 12 2C15.1756 2 18 4.8244 18 8C18 10.3517 18.4669 11.6977 18.8944 12.5528C19.1215 13.007 19.3311 13.3166 19.545 13.673C19.7216 13.9674 20 14.4387 20 15L20 16C20 16.0662 19.9936 16.1309 19.9813 16.1935Z");
  stroke: none;
}

</style>
