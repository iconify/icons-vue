<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="dg7kedy1c"/><path class="k0xylug1p"/><ellipse class="tsz6qlbio"/><path class="ux6s2nbnw"/><path class="i0i01-blm"/><path class="dbjjifdbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-emoji-broken" /></template>
<style>
.dbjjifdbs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8.00337C6.85315 7.36523 8.13392 7 9.5 7C13.6421 7 17 10.3579 17 14.5C17 18.6421 13.6421 22 9.5 22C5.35786 22 2 18.6421 2 14.5C2 13.1339 2.36523 11.8532 3.00337 10.75");
}

.dg7kedy1c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 16L12 16");
}

.i0i01-blm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.9811 2.35316C18.1668 1.88228 18.8332 1.88228 19.0189 2.35316L19.6733 4.01242C19.73 4.15618 19.8438 4.26998 19.9876 4.32668L21.6468 4.98108C22.1177 5.16679 22.1177 5.83321 21.6468 6.01892L19.9876 6.67332C19.8438 6.73002 19.73 6.84382 19.6733 6.98759L19.0189 8.64684C18.8332 9.11772 18.1668 9.11772 17.9811 8.64684L17.3267 6.98759C17.27 6.84382 17.1562 6.73002 17.0124 6.67332L15.3532 6.01892C14.8823 5.83321 14.8823 5.16679 15.3532 4.98108L17.0124 4.32668C17.1562 4.26998 17.27 4.15618 17.3267 4.01242L17.9811 2.35316Z");
}

.k0xylug1p {
  d: path("M13.5 12.5C13.5 13.0523 13.2761 13.5 13 13.5C12.7239 13.5 12.5 13.0523 12.5 12.5C12.5 11.9477 12.7239 11.5 13 11.5C13.2761 11.5 13.5 11.9477 13.5 12.5Z");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.tsz6qlbio {
  cx: 9px;
  cy: 12.5px;
  rx: 0.5px;
  ry: 1px;
}

.ux6s2nbnw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 7L15 9");
}

</style>
