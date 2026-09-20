<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG3rMndcyG" class="ht3z8-bqi"/></defs><clipPath id="SVGBOv6peZo"><use href="#SVG3rMndcyG"/></clipPath><g clip-path="url(#SVGBOv6peZo)"><path class="dju4y770q"/><path class="dsaa5acwi"/><path class="z27tljb4n"/><path class="b9zxx2bma"/><path class="zofh9vrlj"/><path class="eqf5s5-oc"/><path class="bj7-pdbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:3rd-place-medal" /></template>
<style>
.b9zxx2bma {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M96.97 95.97c0 17.67-14.32 31.99-31.99 31.99s-31.99-14.32-31.99-31.99s14.32-31.99 31.99-31.99s31.99 14.33 31.99 31.99");
}

.bj7-pdbna {
  fill: var(--svg-color--ae3d09, #ae3d09);
  d: path("M64.7 111.85h.16c1.81-.03 5.24-.43 7.86-2.78c2.18-1.96 3.19-4.64 2.78-7.36c-.39-2.53-1.98-4.68-4.41-6.01c2.33-1.75 3.73-3.94 3.97-6.22c.24-2.21-.63-4.41-2.5-6.37c-1.88-1.97-4.42-3.01-7.33-3.01c-4.49 0-8.62 2.37-9.87 4.09c-.11.14-.11.34-.01.5l2.79 4.03c.07.1.17.17.29.18c.11.02.24-.01.33-.09c.03-.02 3.06-2.51 5.65-2.51c1.18 0 2.05.52 2.67 1.58c.51.89.61 1.7.3 2.48c-.85 2.1-4.45 3.17-4.48 3.18c-.18.05-.31.22-.31.41v3.55c0 .2.13.37.33.41c.04.01 3.46.86 4.24 2.82c.31.77.15 1.64-.46 2.59c-.65 1-1.63 1.51-2.92 1.51c-2.5 0-5.56-1.9-6.9-3.09a.44.44 0 0 0-.33-.11c-.13.01-.23.08-.3.18l-2.79 4.03c-.11.16-.1.37.03.52c.17.23 4.73 5.49 11.21 5.49");
}

.dju4y770q {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M50.14 61.85h25.59L107.72 0H82.13z");
}

.dsaa5acwi {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M66.13 30.92L53.34 55.67l3.2 6.18h19.19l3.2-6.18z");
}

.eqf5s5-oc {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M77.86 61.85H52.27L20.28 0h25.59z");
}

.ht3z8-bqi {
  d: path("M0 0h128v128H0z");
}

.z27tljb4n {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M77.77 76.78H52.18V61.85h25.59zm0-21.33H52.18a6.4 6.4 0 0 0-6.4 6.4v14.93c0 3.54 2.86 6.4 6.4 6.4h25.59c3.54 0 6.4-2.86 6.4-6.4V61.85c0-3.54-2.86-6.4-6.4-6.4");
}

.zofh9vrlj {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.53 88.19c-.42 0-.84-.08-1.24-.26c-1.54-.66-2.28-2.45-1.68-4.01c.01-.03.02-.05.03-.07c.01-.05.01-.04.04-.08A22.8 22.8 0 0 1 56.56 70.4c.35-.08.72.09.88.42s.07.73-.22.96c-4.67 3.71-8.4 8.72-10.79 14.47c0 .01-.01.02-.01.02c0 .01 0 .01-.01.02c-.33.77-.94 1.37-1.72 1.67c-.37.16-.77.23-1.16.23");
}

</style>
