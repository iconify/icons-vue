<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z11d_gc4d"/><path class="iz_2k3buk"/><path class="h5ryt72zr"/><defs><path id="SVGc4ewPc3U" class="l64zssb2x"/></defs><clipPath id="SVGqsBuUdhR"><use href="#SVGc4ewPc3U"/></clipPath><g clip-path="url(#SVGqsBuUdhR)"><path class="n8om94v6g"/></g><g clip-path="url(#SVGqsBuUdhR)"><path class="zm9756bvc"/></g><g clip-path="url(#SVGqsBuUdhR)"><path class="w33p14b0l"/></g><g clip-path="url(#SVGqsBuUdhR)"><path class="jxgt2tbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:face-with-medical-mask" /></template>
<style>
.h5ryt72zr {
  fill: var(--svg-color--fff, #fff);
  d: path("M92.04 110.37a243.5 243.5 0 0 1-56.08 0C30.45 109.73 26 104.52 26 99V74c0-5.53 4.45-9.27 9.96-8.63c18.63 2.16 37.45 2.16 56.08 0c5.51-.64 9.96 3.1 9.96 8.63v25c0 5.52-4.45 10.73-9.96 11.37");
}

.iz_2k3buk {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M34.98 46.77c.04-.97.21-1.86.43-2.72c1.81-.2 3.76-.51 5.9-1.11c3.17-.85 5.51-2.32 7.35-3.93c2.01 1.89 3.26 4.84 3.16 8.15c-.17 5.57-4.06 10.01-8.72 9.91c-4.65-.11-8.28-4.74-8.12-10.3m57.85 0c-.04-.97-.21-1.86-.43-2.72c-1.81-.2-3.76-.51-5.9-1.11c-3.17-.85-5.51-2.32-7.35-3.93c-2.01 1.89-3.26 4.84-3.16 8.15c.17 5.57 4.06 10.01 8.72 9.91c4.65-.11 8.28-4.74 8.12-10.3");
}

.jxgt2tbcf {
  fill: var(--svg-color--fff, #fff);
  d: path("M31 99.17h-.16c-.78-.04-19.35-1.09-34.48-6.77a2.99 2.99 0 0 1-1.75-3.86a2.99 2.99 0 0 1 3.86-1.75c14.28 5.36 32.51 6.39 32.69 6.4c1.65.09 2.92 1.5 2.84 3.16a3 3 0 0 1-3 2.82");
}

.l64zssb2x {
  d: path("M64.1 9.64C1.79 9.64.31 79.5.31 93.33s28.56 25.03 63.79 25.03c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.46-83.69-63.79-83.69");
}

.n8om94v6g {
  fill: var(--svg-color--fff, #fff);
  d: path("M97.2 80.1c-1.44 0-2.71-1.04-2.95-2.51a3 3 0 0 1 2.46-3.45c.18-.03 18.19-3.13 32.4-12.72c1.38-.93 3.24-.56 4.17.81s.57 3.24-.81 4.17C117.15 76.73 98.49 79.92 97.7 80.06c-.17.02-.33.04-.5.04");
}

.w33p14b0l {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.01 80.1c-.16 0-.33-.01-.5-.04c-.79-.13-19.45-3.32-34.77-13.67c-1.37-.93-1.74-2.79-.81-4.17s2.79-1.74 4.16-.81c14.25 9.62 32.22 12.69 32.4 12.72c1.63.27 2.74 1.82 2.47 3.45a2.99 2.99 0 0 1-2.95 2.52");
}

.z11d_gc4d {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64.11 9.64C1.79 9.64.31 79.5.31 93.33s28.56 25.03 63.79 25.03c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.46-83.69-63.78-83.69");
}

.zm9756bvc {
  fill: var(--svg-color--fff, #fff);
  d: path("M97.2 99.17c-1.58 0-2.91-1.24-2.99-2.84a3.005 3.005 0 0 1 2.83-3.16c.18-.01 18.44-1.05 32.69-6.4a2.997 2.997 0 0 1 2.11 5.61c-15.13 5.68-33.7 6.73-34.48 6.77c-.05.02-.1.02-.16.02");
}

</style>
