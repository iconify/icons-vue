<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g7fhx_bau"/><path class="f91zx1oym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-plus-sharp-two-tone" /></template>
<style>
.f91zx1oym {
  d: path("M15.254 11.0546C16.1706 13.7121 17 14.356 17 15L17 16L3 16L3 15C3 14 5 13 5 8C5 5.2386 7.2386 3 10 3C10.7111 3 11.3875 3.1484 12.9164 3.8164M7.7679 19.134C8.6252 20.6188 9.2855 21 10 21C10.7145 21 11.3748 20.6188 12.2321 19.134M19 1L19 9M15 5L23 5");
}

.g7fhx_bau {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 3.6251L13 8.4199C13 9.793 14.0725 10.9155 15.4255 10.9954L16.1993 10.7285C16.6326 11.9847 17.0404 12.7542 17.3428 13.293C17.5741 13.7052 18 14.341 18 15L18 16C18 16.5523 17.5523 17 17 17L3 17C2.4477 17 2 16.5523 2 16L2 15C2 14.4387 2.2784 13.9674 2.455 13.673C2.6689 13.3166 2.8785 13.007 3.1056 12.5528C3.5331 11.6977 4 10.3517 4 8C4 4.6863 6.6863 2 10 2C10.9153 2 11.7414 2.2118 13.3168 2.9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
