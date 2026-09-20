<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="g6i03gb2s"><path class="c-en8e-lz"/><path class="rmo776bha"/></g><defs><path id="SVGxsLDIchk" class="s1-4cab4j"/></defs><use href="#SVGxsLDIchk" class="ehej3-bmx"/><clipPath id="SVGnjLS8dkR"><use href="#SVGxsLDIchk"/></clipPath><path clip-path="url(#SVGnjLS8dkR)" class="k6dqjiqep"/><defs><path id="SVGgtT2Rcce" class="q383lw70n"/></defs><use href="#SVGgtT2Rcce" class="ehej3-bmx"/><clipPath id="SVG2yuq5cKZ"><use href="#SVGgtT2Rcce"/></clipPath><path clip-path="url(#SVG2yuq5cKZ)" class="q74ow_x-n"/><path class="vkic71b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:angry-face-with-horns" /></template>
<style>
.c-en8e-lz {
  d: path("M64.46 24.82c-58.32 0-59.7 65.38-59.7 78.33c0 12.93 26.75 23.43 59.7 23.43c32.99 0 59.7-10.5 59.7-23.43c.01-12.95-1.37-78.33-59.7-78.33");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.g6i03gb2s {
  fill: var(--svg-color--e75625, #e75625);
}

.k6dqjiqep {
  fill: var(--svg-color--fbb817, #fbb817);
  d: path("M39.47 84.11c-9.17-1.79-9.99-11.04-8.65-14.68l21.47 6.8c-.13 3.62-6.35 9.15-12.82 7.88");
}

.q383lw70n {
  d: path("M90.87 89.86c13.82-2.84 15.27-15.5 14.29-21L70.9 79.11c.97 5.48 10.28 12.73 19.97 10.75");
}

.q74ow_x-n {
  fill: var(--svg-color--fbb817, #fbb817);
  d: path("M89.45 84.11c9.17-1.79 9.99-11.04 8.65-14.68l-21.46 6.8c.12 3.62 6.34 9.15 12.81 7.88");
}

.rmo776bha {
  d: path("M83.92 40.16c.71-2.01 2.2-3.9 4.43-5.65c1.82-1.43 3.75-2.83 5.25-4.61c4.42-5.26 6.58-13.45 5.58-20.29c-.23-1.53-1.72-4.48-.71-5.87c1.75-2.38 6.08.08 7.47 1.45c4.35 4.28 6.96 10.15 8.23 16.05c1.59 7.33 1.37 14.93-1.06 22.03c-2.02 5.88-6.87 11.69-13.12 13.07c-5.36 1.19-11.15-2.35-14.11-6.56c-2.39-3.42-3.01-6.65-1.96-9.62m-38.91-.84c-.71-2-2.18-3.89-4.43-5.65c-1.83-1.43-3.72-2.83-5.24-4.61c-4.41-5.26-6.57-13.44-5.57-20.28c.23-1.54 1.7-4.48.7-5.87c-1.74-2.4-6.07.07-7.47 1.45c-4.34 4.28-6.95 10.15-8.24 16.04c-1.57 7.32-1.36 14.93 1.08 22.03c2.01 5.88 6.88 11.69 13.12 13.08c5.35 1.19 11.14-2.36 14.08-6.56c2.4-3.43 3.03-6.65 1.97-9.63");
}

.s1-4cab4j {
  d: path("M38.06 89.86c-13.82-2.84-15.27-15.5-14.29-21l34.26 10.26c-.97 5.47-10.27 12.72-19.97 10.74");
}

.vkic71b_u {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M63.18 98.3c.63 0 1.31.03 1.98.06c15.84.95 21.84 9.54 22.09 9.9c.9 1.3.54 3.06-.74 3.94c-1.29.88-3.03.54-3.92-.73c-.23-.32-4.93-6.69-17.77-7.44c-12.8-.74-18.38 7.62-18.45 7.7c-.83 1.31-2.6 1.69-3.91.84a2.817 2.817 0 0 1-.83-3.91c.28-.46 6.86-10.36 21.55-10.36");
}

</style>
