<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVG47aqDHPK" cx="64" cy="-862.9" r="56.96" fx="64" fy="-862.9" gradientTransform="matrix(1 0 0 -1 0 -800)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><clipPath id="SVGGPZ1Yb5H"><path class="wpg8al5vc"/></clipPath></defs><g class="wj4kgr0on"><path fill="url(#SVG47aqDHPK)" class="vx4yod9me"/><path class="krzinnb4c"/></g><path class="o5wef0b-h"/><path class="wvcoby32y"/><path class="dlzigefqb"/><path class="kp6j28boj"/><g clip-path="url(#SVGGPZ1Yb5H)"><path class="t3a5v43jg"/></g><g class="wj4kgr0on"><path class="q54gfqbvu"/><path class="d969aecmc"/></g><path class="pmoahgrwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-tongue" /></template>
<style>
.d969aecmc {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M64.72 106.25c1.1 0 1.99-.89 1.99-1.99V85c-.91.01-1.81.03-2.73.03c-.42 0-.84 0-1.26-.01v19.24c0 1.1.89 1.99 1.99 1.99Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.dlzigefqb {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 46.94c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.kp6j28boj {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 50.87c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.krzinnb4c {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 29.67c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 110.52 44.81 118.8 64 118.8c15.4 0 29.8-5.2 40.4-14.5C115.9 94.1 122 79.8 122 62.9c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.o5wef0b-h {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M44.82 46.94c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.pmoahgrwk {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M66.71 85h-3.99c-5.73 0-11.38-.27-16.81-.72v3.55c4.74 1.07 18.8 3.48 37.61-.22v-3.46c-5.42.49-11.06.78-16.81.85");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q54gfqbvu {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M66.71 85c-.91.01-1.81.03-2.73.03c-.42 0-.84 0-1.26-.01c-5.73-.03-11.38-.27-16.81-.72v24.58c0 9.48 7.69 17.17 17.17 17.17h3.27c9.48 0 17.17-7.69 17.17-17.17V84.17c-5.42.49-11.06.77-16.81.84Z");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.t3a5v43jg {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M63.99 80.43c-12.68 0-24.48-1.06-34.31-2.88c-2.44-.45-4.6 1.69-4.1 4.12c3.27 16 19.02 29.13 38.4 29.13c21.21 0 35.49-13.57 38.45-29.19c.46-2.41-1.69-4.52-4.11-4.07c-9.84 1.82-21.64 2.89-34.33 2.89");
}

.vx4yod9me {
  d: path("M64 118.8c-27.9 0-58-17.5-58-55.9S36.1 7 64 7c15.5 0 29.8 5.1 40.4 14.4C115.9 31.6 122 46 122 62.9s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.wpg8al5vc {
  fill: none;
  stroke-width: var(--svg-stroke-width--0px, 0px);
  d: path("M63.99 80.43c-12.68 0-24.48-1.06-34.31-2.88c-2.44-.45-4.6 1.69-4.1 4.12c3.27 16 19.02 29.13 38.4 29.13c21.21 0 35.49-13.57 38.45-29.19c.46-2.41-1.69-4.52-4.11-4.07c-9.84 1.82-21.64 2.89-34.33 2.89");
}

.wvcoby32y {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 50.87c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

</style>
