<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG3rMndcyG" class="ht3z8-bqi"/></defs><clipPath id="SVGBOv6peZo"><use href="#SVG3rMndcyG"/></clipPath><g clip-path="url(#SVGBOv6peZo)"><path class="bsq5xc82t"/><path class="k3_x2sn2q"/><path class="ghhi2m-au"/><path class="kzls-vbxi"/><path class="jsp0_1qsn"/><path class="rqxlwbbjc"/><path class="n1aaukbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:1st-place-medal" /></template>
<style>
.bsq5xc82t {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M48.87 61.82h25.58L106.43 0H80.85z");
}

.ghhi2m-au {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M76.5 76.75H50.92V61.82H76.5zm0-21.32H50.92a6.4 6.4 0 0 0-6.4 6.4v14.92a6.4 6.4 0 0 0 6.4 6.4H76.5c3.53 0 6.39-2.86 6.39-6.4V61.82c0-3.53-2.86-6.39-6.39-6.39");
}

.ht3z8-bqi {
  d: path("M0 0h128v128H0z");
}

.jsp0_1qsn {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.27 88.15c-.42 0-.84-.08-1.24-.26c-1.54-.66-2.28-2.45-1.68-4c.01-.02.02-.05.02-.07c.01-.05.02-.04.04-.08c2.83-6.74 8.76-11.72 15.88-13.37c.35-.08.72.09.88.42s.07.73-.22.96c-4.67 3.71-8.4 8.71-10.78 14.47c0 .01-.01.02-.01.02s0 .01-.01.01c-.33.77-.94 1.37-1.72 1.67c-.37.16-.77.23-1.16.23");
}

.k3_x2sn2q {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64.86 30.91L52.07 55.64l3.2 6.18h19.18l3.2-6.18z");
}

.kzls-vbxi {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M95.68 95.93c0 17.66-14.32 31.98-31.98 31.98S31.72 113.6 31.72 95.93S46.04 63.95 63.7 63.95c17.67 0 31.98 14.32 31.98 31.98");
}

.n1aaukbva {
  fill: var(--svg-color--f79329, #f79329);
  d: path("m57.5 89.41l2.97-.85v16.31h-2.29c-.25 0-.44.2-.44.44v5.58c0 .24.19.44.44.44h11.85c.24 0 .44-.2.44-.44v-5.58c0-.24-.2-.44-.44-.44h-2.29V80.98c0-.13-.06-.26-.17-.34a.45.45 0 0 0-.37-.09l-9.92 2.13c-.2.05-.35.22-.35.43v5.88c0 .13.06.27.17.35c.13.08.27.1.4.07");
}

.rqxlwbbjc {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M76.59 61.82H51L19.03 0h25.58z");
}

</style>
