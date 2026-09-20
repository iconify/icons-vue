<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVG9pw49bDS" cx="62.6" cy="64" r="56.96" fx="62.6" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGnRyGNwTV" cx="79.08" cy="54.29" r="51.47" fx="79.08" fy="54.29" gradientTransform="matrix(1 0 0 .72 0 15.24)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="r_-r4-l8z"/><stop offset=".85" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><linearGradient id="SVGC8zcIdHL" x1="73.88" x2="145.87" y1="83.34" y2="83.34" gradientUnits="userSpaceOnUse"><stop offset="0" class="izds9pb9v"/><stop offset=".2" class="fy29b14mj"/><stop offset="1" class="rj9n7wupy"/></linearGradient></defs><path fill="url(#SVG9pw49bDS)" class="vc1p1676l"/><path class="sfac9zbjl"/><path class="mzwfv_bfa"/><path class="skm81gt3f"/><path fill="url(#SVGnRyGNwTV)" class="br2p-3l3k"/><path class="oynhjl5_t"/><path class="cyp0szova"/><path fill="url(#SVGC8zcIdHL)" class="yujg4z1ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:lying-face" /></template>
<style>
.br2p-3l3k {
  d: path("M120.6 74.28H70.05V58.64h50.55s5.41 1.6 5.73 7.67s-5.73 7.97-5.73 7.97");
}

.cyp0szova {
  fill: none;
  d: path("M120.67 63.31c-.07 1.83-2.08 2.73-3.86 2.72c-1.78 0-9.05-.25-10.41-.26c-1.35 0-2.96-.99-2.96-2.35c0-1.27.46-2.3 2.89-2.53c2.83-.27 8.99-.36 11.09-.36s3.32.95 3.25 2.78");
}

.fy29b14mj {
  stop-color: var(--svg-color--rgba-235-143-0-36, rgba(235, 143, 0, .36));
  stop-opacity: 0.36;
}

.izds9pb9v {
  stop-color: var(--svg-color--eb8f00, #eb8f00);
  stop-opacity: 0.3;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mzwfv_bfa {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M58.3 91.6c7.1-2.3 13.4-.3 15.7 1.6c.9.7 1.3 1.6 1.2 2.5c-.1.7-.6 1.1-1.2 1.4c-.2.1-.5.1-.7.1c-3.9 0-8.3.8-12.4 2.1c-4.2 1.4-8.1 3.3-11.3 5.6c-.2.1-.4.3-.6.3c-.6.2-1.3.1-1.8-.4c-.6-.6-.8-1.6-.5-2.7c.6-2.8 4.5-8.1 11.6-10.5M30.06 41.59c-1.65 1.51-4.26-.35-2.88-2.32c2.89-3.96 7.53-7.09 13.04-8.05c1.94-.41 4-.47 5.82-.22c2.48.38 1.98 3.51-.14 3.66l-.14.02c-6 .46-11.64 3.08-15.69 6.91Zm63.69-6.14c1.54 1.62 4.27-.05 3.04-2.11c-2.6-4.15-7.01-7.6-12.44-8.95c-1.91-.54-3.96-.75-5.79-.63c-2.5.2-2.22 3.37-.11 3.66l.14.03c5.96.88 11.4 3.89 15.16 8M89.8 55.5c0-5.9-3.8-9.4-8-9.4s-8 3.5-8 9.4c0 .97.11 1.87.3 2.7h15.4c.19-.83.3-1.73.3-2.7m-45.6-9.4c-4.2 0-8 3.5-8 9.4s3.8 9.4 8 9.4s8-3.5 8-9.4s-3.8-9.4-8-9.4");
}

.oynhjl5_t {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M117.55 56.68c-2.98 0-43.75.74-45.89.78s-2.18 2.24 0 2.24s42.9-.02 45.89-.02c3.66 0 6.64 2.98 6.64 6.64s-3.23 6.7-6.89 6.7c-2.98 0-43.44-.08-45.63-.08s-2.1 2.61.04 2.65c2.13.04 42.74.86 45.72.86c6.81 0 9.76-4.81 9.76-10.13s-4.32-9.64-9.64-9.64");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.rj9n7wupy {
  stop-color: var(--svg-color--eb8f00, #eb8f00);
  stop-opacity: 0.6;
}

.sfac9zbjl {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M110.49 30.77c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94c10.76 17.66 30.99 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.skm81gt3f {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.36 50.29c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69m37.22 0c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.vc1p1676l {
  d: path("M62.6 119.9c-27.9 0-58-17.5-58-55.9s30.1-55.9 58-55.9c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.yujg4z1ry {
  d: path("M78.06 75.33c7.83 1.11 13.62 2.16 19.98 4.89c5.35 2.29 10.53 5.65 13.69 11.12c0 0 6.51-9.49 6.28-15.77l-39.96-.24Z");
}

</style>
