<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGCPdGFatC" cx="63.81" cy="24" r="56.96" fx="63.81" fy="24" gradientTransform="matrix(1 0 0 -1 0 88)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGCPdGFatC)" class="hrllw020i"/><path class="l8ukinbqx"/></g><path class="mpzcubckm"/><path class="n74h-bbhb"/><path class="jf00rc3go"/><path class="xp5evsbxg"/><g class="wj4kgr0on"><path class="wftzaolpz"/><path class="ffqs2pb6l"/><path class="u-y3wttnn"/><path class="ct_8dkr3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:grinning-face" /></template>
<style>
.ct_8dkr3b {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M102.75 72.73c-1.33-2.46-4.19-3.55-7.19-2.61c-8.96 2.8-20.46 4.42-31.59 4.43c-11.12-.01-22.63-1.63-31.59-4.43c-2.99-.93-5.81.14-7.14 2.6c-1.36 2.52-.37 5.42.77 7.94c.52 1.14 1.09 2.24 1.71 3.31c0 0-2.13-7.8-.28-10.06c.76-.92 2.57-1.6 4.63-1c9.2 2.69 20.79 4.26 31.89 4.37s22.91-1.87 32.34-4.76c2.11-.65 3.43.48 4.19 1.4c1.85 2.26-.28 10.07-.28 10.07c.62-1.07 1.24-2.16 1.76-3.3c1.14-2.51 2.13-5.42.77-7.94Z");
}

.ffqs2pb6l {
  fill: var(--svg-color--ed7770, #ed7770);
  d: path("M64.05 92.86c-13.11-.32-17.18 6.82-17.42 7.14c2.4 1.22 9.9 3.34 17.12 3.38s14.53-2.01 16.88-3.04c-.17-.33-3.48-7.16-16.59-7.47Z");
}

.hrllw020i {
  d: path("M63.81 119.9c-27.9 0-58-17.5-58-55.9s30.1-55.9 58-55.9c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.jf00rc3go {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.l8ukinbqx {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M112.08 30.77c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.77 111.62 45 119.9 64.19 119.9c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mpzcubckm {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M44.82 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.n74h-bbhb {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.u-y3wttnn {
  fill: var(--svg-color--fff, #fff);
  d: path("M95.56 71.15c-8.96 2.8-20.66 4.67-31.79 4.68c-11.12-.01-21.98-1.72-30.94-4.53c-2.99-.93-5.28-.93-6.6 1.54c-.21.39-.72 1.42-.26 1.59c12.1 6.17 25.16 8.93 38.8 8.93s25.64-2.55 37.33-8.21c.47-.2-.15-1.71-.48-2.32c-1.33-2.46-3.07-2.63-6.07-1.69Z");
}

.wftzaolpz {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M101.54 72.9c-1.33-2.46-3.83-2.77-6.83-1.83c-8.96 2.8-19.52 4.23-30.65 4.25c-11.12-.01-22.85-1.53-31.81-4.33c-2.99-.93-4.59-.3-5.91 2.17c-1.36 2.52-1.45 4.99-.31 7.5c6.42 14.1 21.84 23.01 38.04 22.59c18.63-.48 31.45-8.49 37.87-22.59c1.14-2.51.96-5.23-.4-7.75Z");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.xp5evsbxg {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

</style>
