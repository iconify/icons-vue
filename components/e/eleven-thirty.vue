<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGVLCSR1oI" class="vhvda676h"/><path id="SVGdZrRpsTW" class="xnpm8wb3j"/></defs><use href="#SVGVLCSR1oI" class="n1mjunbsu"/><path class="i6dzqlqmx"/><circle class="y1ws6sb7x"/><path class="t7550gbkm"/><g class="ehej3-bmx"><use href="#SVGdZrRpsTW"/><use href="#SVGdZrRpsTW"/></g><path class="m2vwdub1t"/><circle class="upcif2bnq"/><path class="ayexmobot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:eleven-thirty" /></template>
<style>
.ayexmobot {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M90.81 17.57a3.69 3.69 0 0 1 1.34 5.04c-1.01 1.76-3.27 2.36-5.03 1.35a3.69 3.69 0 0 1-1.34-5.04a3.67 3.67 0 0 1 5.03-1.35m-26.82-7.19c-2.03 0-3.68 1.65-3.68 3.68c0 2.04 1.65 3.68 3.68 3.68c2.04 0 3.69-1.65 3.69-3.68s-1.65-3.68-3.69-3.68");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.i6dzqlqmx {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.9C28.77 127.9.1 99.23.1 64S28.77.1 64 .1s63.89 28.67 63.89 63.9S99.23 127.9 64 127.9M64 6.27C32.17 6.27 6.27 32.17 6.27 64c0 31.84 25.9 57.73 57.73 57.73s57.74-25.9 57.74-57.73S95.83 6.27 64 6.27");
}

.m2vwdub1t {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m50.655 33.152l8.864-2.463l9.825 35.36l-8.865 2.463z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.t7550gbkm {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M110.43 37.2c1.02 1.76.41 4.01-1.35 5.04c-1.77 1.01-4.02.41-5.03-1.35a3.69 3.69 0 0 1 1.35-5.04a3.67 3.67 0 0 1 5.03 1.35M90.81 17.57a3.68 3.68 0 0 1 1.34 5.03c-1.01 1.76-3.27 2.36-5.03 1.35a3.68 3.68 0 0 1-1.34-5.03a3.67 3.67 0 0 1 5.03-1.35m-53.62 0a3.68 3.68 0 0 1 5.03 1.35c1.02 1.76.42 4.01-1.35 5.03a3.67 3.67 0 0 1-5.03-1.35c-1.01-1.76-.41-4.02 1.35-5.03M17.56 37.19a3.69 3.69 0 0 1 5.04-1.35a3.67 3.67 0 0 1 1.34 5.03a3.673 3.673 0 0 1-5.03 1.35c-1.76-1.01-2.36-3.27-1.35-5.03M10.38 64c0-2.03 1.65-3.68 3.68-3.68s3.67 1.65 3.67 3.68c0 2.04-1.64 3.69-3.67 3.68c-2.03 0-3.69-1.65-3.68-3.68m7.18 26.81a3.69 3.69 0 0 1 1.35-5.03a3.68 3.68 0 0 1 5.03 1.35c1.02 1.77.41 4.02-1.36 5.04c-1.75 1.01-4 .4-5.02-1.36m19.63 19.62a3.69 3.69 0 0 1-1.35-5.03a3.694 3.694 0 0 1 5.04-1.35a3.673 3.673 0 0 1 1.35 5.03c-1.03 1.77-3.29 2.38-5.04 1.35m53.61 0a3.68 3.68 0 0 1-5.03-1.35a3.68 3.68 0 0 1 1.33-5.03c1.77-1.02 4.03-.41 5.04 1.34c1.03 1.77.42 4.03-1.34 5.04m19.63-19.62a3.68 3.68 0 0 1-5.03 1.34a3.67 3.67 0 0 1-1.35-5.03a3.68 3.68 0 0 1 5.03-1.35c1.76 1.02 2.37 3.29 1.35 5.04M59.4 60.61h9.2v56.05h-9.2z");
}

.upcif2bnq {
  cx: 64px;
  cy: 64px;
  r: 3.69px;
  fill: var(--svg-color--fff, #fff);
}

.vhvda676h {
  d: path("M64 6.27C32.17 6.27 6.27 32.17 6.27 64c0 31.84 25.9 57.73 57.73 57.73s57.74-25.9 57.74-57.73S95.83 6.27 64 6.27");
}

.xnpm8wb3j {
  d: path("M73.78 63.99c0 5.41-4.39 9.79-9.78 9.79c-5.4 0-9.78-4.38-9.78-9.79c0-5.4 4.38-9.77 9.78-9.77c5.39 0 9.78 4.37 9.78 9.77");
}

.y1ws6sb7x {
  cx: 113.93px;
  cy: 64px;
  r: 3.69px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
