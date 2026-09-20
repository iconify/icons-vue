<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pub-vc0ql"/><path class="w2d7t-bek"/><path class="g0qravb6n"/><ellipse class="bh60_-o1s"/><path class="hwd_74d2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:flag-in-hole" /></template>
<style>
.bh60_-o1s {
  cx: 37.46px;
  cy: 91.1px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 16.62px;
  ry: 5.5px;
}

.g0qravb6n {
  fill: var(--svg-color--626e30, #626e30);
  d: path("M43.31 91.73L64.4 66.52c-2.79.08-5.7.24-8.71.49L40.37 89.26z");
}

.hwd_74d2v {
  fill: var(--svg-color--fbb817, #fbb817);
  d: path("M37.58 96.56c.15 0 .3 0 .45-.01V8.5a1.786 1.786 0 0 0-3.57 0v87.96c1.01.06 2.05.1 3.12.1");
}

.pub-vc0ql {
  fill: var(--svg-color--e75625, #e75625);
  d: path("m35.7 7.67l.54 38.25s7.03-2.58 12.04-7.28c4.54-4.26 14.39-6.46 21.01-8.84C83.94 24.54 86.7 19.08 86.7 19.08s.24 1.26-12.61-.27c-3.64-.43-12.44-2.58-17.03-3.88c-5.33-1.51-6.8-2.2-10.26-3.45c-7.67-2.79-9.47-3.81-9.47-3.81z");
}

.w2d7t-bek {
  fill: var(--svg-color--a2c02b, #a2c02b);
  d: path("M3.34 82.86s3.77-7.62 33.68-13.28c27.59-5.22 48.16-3.15 61.07.81c30.28 9.27-7.58 14.53 4.02 22.11c9.76 6.38 24.71 4.58 24.89 13.08c.13 5.79-14.43 9.79-34.23 11.01c-44.87 2.77-73.31-8.98-83.04-15.01c-8.31-5.16-11.26-13.12-6.39-18.72");
}

</style>
