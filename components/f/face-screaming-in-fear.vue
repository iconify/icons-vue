<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGN3GC8bgi" x1="64" x2="64" y1="66.667" y2="4.276" gradientUnits="userSpaceOnUse"><stop offset="0" class="gd0gtsapz"/><stop offset=".151" class="ytgu838_q"/><stop offset=".473" class="jg22bvwgp"/><stop offset=".935" class="v3br35bqe"/><stop offset="1" class="edl656b9v"/></linearGradient><path fill="url(#SVGN3GC8bgi)" class="liu2giwjy"/><path class="gt8koto2m"/><ellipse transform="rotate(-83.65 85.943 45.291)" class="tepg_h3xg"/><path class="i7fw9fbgq"/><ellipse transform="rotate(-4.313 42.443 45.283)" class="cbd9e213j"/><path class="be1p4zb_g"/><path class="c4nshvb4p"/><path class="rdxgsnb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:face-screaming-in-fear" /></template>
<style>
.be1p4zb_g {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M49.02 44.03c.38 3.29-2.01 6.3-5.34 6.72c-3.34.43-6.36-1.9-6.74-5.18c-.4-3.29 1.99-6.3 5.33-6.73c3.33-.42 6.36 1.9 6.75 5.19");
}

.c4nshvb4p {
  fill: none;
  d: path("M64 9.64C1.69 9.64.21 79.5.21 93.33S28.77 118.36 64 118.36c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

.cbd9e213j {
  cx: 42.46px;
  cy: 45.3px;
  fill: var(--svg-color--fff, #fff);
  rx: 15.5px;
  ry: 16.61px;
}

.edl656b9v {
  stop-color: var(--svg-color--42ade7, #42ade7);
}

.gd0gtsapz {
  stop-color: var(--svg-color--fcc21b, #fcc21b);
}

.gt8koto2m {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M80.46 90.47c0 14.09-7.37 20.03-16.46 20.03s-16.46-5.94-16.46-20.03s7.37-31 16.46-31s16.46 16.91 16.46 31");
}

.i7fw9fbgq {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M92.63 45.26c-.23 3.3-3.14 5.82-6.49 5.62c-3.36-.19-5.9-3.04-5.67-6.34c.22-3.31 3.12-5.82 6.48-5.62c3.36.19 5.91 3.03 5.68 6.34");
}

.jg22bvwgp {
  stop-color: var(--svg-color--abb973, #abb973);
}

.liu2giwjy {
  d: path("M64 9.64C1.69 9.64.21 79.5.21 93.33S28.77 118.36 64 118.36c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

.rdxgsnb3t {
  fill: var(--svg-color--e48c15, #e48c15);
  d: path("M29.08 121.23c4.69 1.33 10.12-.73 10.24-5.2l.66-14.77c.02-.24 1.08-16.03-7.09-24.46l-.12-.13c-5.75-6.76-8.27-11.55-10.85-19.98c-.86-2.79-2.89-5.41-6.38-4.99c-2.47.3-4.85 1.35-4.69 9.23c.19 9.18 2.02 18.32 5.7 24.72c5.14 8.95 3.8 19.17 4.36 25.72c.34 4.11 3.23 8.63 8.17 9.86m69.84 0c-4.69 1.33-10.12-.73-10.24-5.2l-.66-14.77c-.02-.24-1.08-16.03 7.09-24.46l.12-.13c5.75-6.76 8.27-11.55 10.85-19.98c.86-2.79 2.89-5.41 6.38-4.99c2.47.3 4.85 1.35 4.69 9.23c-.19 9.18-2.02 18.32-5.7 24.72c-5.14 8.95-3.8 19.17-4.36 25.72c-.34 4.11-3.23 8.63-8.17 9.86");
}

.tepg_h3xg {
  cx: 85.95px;
  cy: 45.29px;
  fill: var(--svg-color--fff, #fff);
  rx: 16.61px;
  ry: 15.5px;
}

.v3br35bqe {
  stop-color: var(--svg-color--4fafd8, #4fafd8);
}

.ytgu838_q {
  stop-color: var(--svg-color--e5bf34, #e5bf34);
}

</style>
