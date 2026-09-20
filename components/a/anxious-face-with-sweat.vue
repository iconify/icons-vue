<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGwkAPLdaz" cx="64.53" cy="64" r="56.96" fx="64.53" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGLY7NubWy" cx="21.52" cy="606.94" r="33.4" fx="21.52" fy="606.94" gradientTransform="matrix(1 0 0 1.54 0 -870.65)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="v1-56mb1l"/><stop offset="1" class="r5vbxk1ae"/></radialGradient><linearGradient id="SVGF8ZTpzsy" x1="64.53" x2="64.53" y1="-1511.9" y2="-1400.1" gradientTransform="matrix(1 0 0 -1 0 -1392)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="lfxua2bme"/><stop offset=".6" class="qi1mj4bge"/><stop offset=".68" class="auri2bbpz"/><stop offset=".76" class="vh1kshkig"/><stop offset=".84" class="ufzqoebgv"/><stop offset=".9" class="s-4dl9bha"/><stop offset=".96" class="vtg5xgcnv"/><stop offset="1" class="zvhoujbdx"/></linearGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGwkAPLdaz)" class="ny4wlh6_j"/><path class="c7d1djb4b"/><path fill="url(#SVGF8ZTpzsy)" class="ny4wlh6_j"/><path fill="url(#SVGLY7NubWy)" class="a43p86o4x"/><path class="vfg0ykisc"/></g><path class="s-mewxbfc"/><path class="q5k2gmb7j"/><path class="b267d-7yz"/><path class="meampx1cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:anxious-face-with-sweat" /></template>
<style>
.a43p86o4x {
  d: path("M20.45 108.14c-8.46 0-14.97-8.2-14.97-15.23c0-4.95 2.21-10.68 5.34-18.62c.39-1.17.91-2.34 1.43-3.65c1.49-3.72 2.81-7.75 4.81-11.24c1.36-2.38 4.83-2.38 6.14.03c1.86 3.43 3.14 7.14 5.07 11.47c5.47 12.24 7.03 17.18 7.03 22.13c.13 6.9-6.51 15.1-14.84 15.1Z");
}

.auri2bbpz {
  stop-color: var(--svg-color--rgba-76-164-240-4, rgba(76, 164, 240, .4));
  stop-opacity: 0.4;
}

.b267d-7yz {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 56.41c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.c7d1djb4b {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M112.42 30.77c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94c10.76 17.66 30.99 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.lfxua2bme {
  stop-color: var(--svg-color--40c0e7, #40c0e7);
  stop-opacity: 0;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.meampx1cx {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 60.34c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.ny4wlh6_j {
  d: path("M64.53 119.9c-27.9 0-58-17.5-58-55.9s30.1-55.9 58-55.9c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.q5k2gmb7j {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 60.34c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.qi1mj4bge {
  stop-color: var(--svg-color--rgba-68-182-234-14, rgba(68, 182, 234, .14));
  stop-opacity: 0.14;
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.s-4dl9bha {
  stop-color: var(--svg-color--rgba-91-128-252-9, rgba(91, 128, 252, .9));
  stop-opacity: 0.9;
}

.s-mewxbfc {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64.03 102.48c3.85 0 7.73.74 11.37 1.74c7.99 3.37 14.37-4.69 9.9-10.02c-4.66-5.54-12.25-7.68-21.53-7.68S47.66 88.14 43 93.69c-5.19 5.29 1.81 13.34 9.81 10.52c3.62-.99 7.36-1.74 11.21-1.74ZM27.12 46.24c-2.2.39-2.31 3.59.09 3.7c4.9.12 10.21-1.66 14.32-5.45c1.5-1.29 2.81-2.89 3.72-4.49c1.21-2.2-1.59-3.71-2.99-2.11l-.1.1c-4.02 4.49-9.53 7.37-15.03 8.24Zm58.73-8.25l-.1-.1c-1.41-1.59-4.2-.08-2.99 2.11c.91 1.6 2.21 3.19 3.72 4.49c4.11 3.78 9.42 5.57 14.32 5.45c2.4-.11 2.29-3.31.09-3.7c-5.5-.88-11.01-3.76-15.03-8.24ZM44.82 56.41c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.ufzqoebgv {
  stop-color: var(--svg-color--rgba-88-137-249-78, rgba(88, 137, 249, .78));
  stop-opacity: 0.78;
}

.v1-56mb1l {
  stop-color: var(--svg-color--29b6f6, #29b6f6);
}

.vfg0ykisc {
  fill: var(--svg-color--a1ebff, #a1ebff);
  d: path("M10.2 94.88c1.84 4.62 6.37 3.39 7.29-.93c.69-3.24-1-12.52-1.67-14.32s-2.47-1.39-3.35.93c-.74 1.94-4.09 9.74-2.26 14.32Z");
}

.vh1kshkig {
  stop-color: var(--svg-color--rgba-82-149-245-61, rgba(82, 149, 245, .61));
  stop-opacity: 0.61;
}

.vtg5xgcnv {
  stop-color: var(--svg-color--rgba-94-123-254-97, rgba(94, 123, 254, .97));
  stop-opacity: 0.97;
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.zvhoujbdx {
  stop-color: var(--svg-color--5f7aff, #5f7aff);
}

</style>
