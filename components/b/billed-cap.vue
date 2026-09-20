<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cmlvaybag"/><path class="niwaw_b2n"/><path class="m4kyyabtc"/><path class="yyexotbnt"/><path class="n9_v7m4qt"/><path class="hb-q4ogfy"/><path class="sb0c4xe2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:billed-cap" /></template>
<style>
.cmlvaybag {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M32.33 67.91s4.16-21.83 11.44-31.19C48.37 30.8 68.73 18 88.48 23.2l1.8.29c2.21 4.6 7.34 16.38 7.16 22.74C97.17 56.19 92 85.62 92 85.62S79.94 81.12 72.98 78C49.44 67.47 32.33 67.91 32.33 67.91");
}

.hb-q4ogfy {
  fill: var(--svg-color--76c8ff, #76c8ff);
  d: path("m7.56 86.27l24.78-18.36s5.16-.98 17 .97c14.38 2.37 49.52 18.28 49.52 18.28l-17.42 14.5s-10.96 8.52-22.04 3.42c-16.56-7.63-34.47-17.56-39.66-18.73c-10.11-2.3-12.18-.08-12.18-.08");
}

.m4kyyabtc {
  fill: none;
  stroke: var(--svg-color--0f60b2, #0f60b2);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2-079px, 2.079px);
  d: path("M48.84 71.16c0-.44 6.39-29.37 13.07-35.6c6.22-5.81 21.65-13.29 21.65-13.29l6.58 1.4s6.67 13.74 7.17 21.18c.69 10.25-5.16 40.94-5.16 40.94");
}

.n9_v7m4qt {
  fill: var(--svg-color--0d47a1, #0d47a1);
  d: path("M5.26 93.26c-.09 1.02-.03 4.01 3.65 2.27s11.31-7.5 11.31-7.5s-7.42-2.77-11.33-.44s-3.54 4.65-3.63 5.67");
}

.niwaw_b2n {
  fill: var(--svg-color--1e88e5, #1e88e5);
  d: path("M97.1 42.89c-.33-1.56-7.05-19.4-7.05-19.4s13.19 3.42 22.99 13.75c4.67 4.92 10.09 11.17 10.79 18.19c1.04 10.39-3.11 32.2-3.12 32.23c-.14.73-7.38.78-7.95.79c-3.26.07-14.55-.36-21.04-3.01c.01 0 6.63-36.55 5.38-42.55");
}

.sb0c4xe2g {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M62.94 108.11c-7.83-1.94-34.43-16.84-43.1-19.5c-2.59-.79-7.01-1.69-9.77-.23c-2.4 1.27-4.45 3.77-3.8 6.64c.1.44.31.92.74 1.04c-.97.38-2.11-.24-2.61-1.15s-.47-2.02-.26-3.04c.43-2.08 1.66-4.37 3.42-5.6c2.33-1.63 6.43-2.73 13.35-.59c12.14 3.75 36.32 18.07 42.57 19.36c9.19 1.89 16.6-3.67 18.85-4.97c2.25-1.31 2.08-.27.52.88c-1.55 1.15-10.02 9.61-19.91 7.16");
}

.yyexotbnt {
  fill: var(--svg-color--0f60b2, #0f60b2);
  d: path("M82.03 21.18c.26-1.24 2.79-2.14 5.65-1.54s4.97 2.48 4.71 3.72s-2.72.62-5.58.01s-5.04-.95-4.78-2.19");
}

</style>
