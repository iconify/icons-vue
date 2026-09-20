<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVG9SzOgJjz" x1="63.79" x2="63.79" y1="65.667" y2="3.276" gradientUnits="userSpaceOnUse"><stop offset="0" class="gd0gtsapz"/><stop offset=".151" class="ytgu838_q"/><stop offset=".473" class="jg22bvwgp"/><stop offset=".935" class="v3br35bqe"/><stop offset="1" class="edl656b9v"/></linearGradient><path fill="url(#SVG9SzOgJjz)" class="zixn6-blk"/><ellipse transform="rotate(-83.65 85.733 47.392)" class="m9x_m6b0w"/><path class="hmn7r2bmv"/><ellipse transform="rotate(-4.313 42.233 47.383)" class="ic_wg-b9i"/><path class="al0gj4gme"/><path class="me-9lw2ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:fearful-face" /></template>
<style>
.al0gj4gme {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M48.81 46.13c.38 3.29-2.01 6.3-5.34 6.72c-3.34.43-6.36-1.9-6.74-5.18c-.4-3.29 1.99-6.3 5.33-6.73c3.33-.42 6.36 1.91 6.75 5.19");
}

.edl656b9v {
  stop-color: var(--svg-color--42ade7, #42ade7);
}

.gd0gtsapz {
  stop-color: var(--svg-color--fcc21b, #fcc21b);
}

.hmn7r2bmv {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M92.42 47.36c-.23 3.3-3.14 5.82-6.49 5.62c-3.36-.19-5.9-3.04-5.67-6.34c.22-3.31 3.12-5.82 6.48-5.62c3.36.19 5.91 3.04 5.68 6.34");
}

.ic_wg-b9i {
  cx: 42.25px;
  cy: 47.4px;
  fill: var(--svg-color--fff, #fff);
  rx: 15.5px;
  ry: 16.61px;
}

.jg22bvwgp {
  stop-color: var(--svg-color--abb973, #abb973);
}

.m9x_m6b0w {
  cx: 85.74px;
  cy: 47.39px;
  fill: var(--svg-color--fff, #fff);
  rx: 16.61px;
  ry: 15.5px;
}

.me-9lw2ks {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M90.82 86.49c-5.14-9.65-13.42-13.3-23.65-14.34c-.97-.09-2.04-.14-3.17-.15c-1.13.01-2.2.06-3.17.16C50.6 73.2 42.32 76.85 37.18 86.5c-3.44 6.46-2.83 12.66 1.97 16.01c2.47 1.72 7.35 1.62 10.43.65c3.32-1.05 7.49-2.89 12.81-3c.54-.01 1.08.01 1.6.05c.53-.04 1.06-.06 1.6-.05c5.32.11 9.49 1.96 12.81 3c3.08.97 7.97 1.07 10.43-.65c4.82-3.36 5.43-9.55 1.99-16.02");
}

.v3br35bqe {
  stop-color: var(--svg-color--4fafd8, #4fafd8);
}

.ytgu838_q {
  stop-color: var(--svg-color--e5bf34, #e5bf34);
}

.zixn6-blk {
  d: path("M63.79 8.64C1.48 8.64 0 78.5 0 92.33s28.56 25.03 63.79 25.03c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

</style>
