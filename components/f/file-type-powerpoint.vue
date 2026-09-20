<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGNTQfxeQw" x1="4.494" x2="13.832" y1="-1748.086" y2="-1731.914" gradientTransform="translate(0 1756)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ljf15lm1f"/><stop offset=".5" class="u-o_sr-1l"/><stop offset="1" class="w842ttblp"/></linearGradient></defs><path class="z612e-6xk"/><path class="v306jcbxc"/><path class="w_urqz91r"/><path class="afu8wxbrj"/><path class="g8l4hwrvx"/><path class="h4lu0cl9n"/><path class="xt94p9b6e"/><path fill="url(#SVGNTQfxeQw)" class="lugf9nb5a"/><path class="xjc2kf1uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powerpoint" /></template>
<style>
.afu8wxbrj {
  d: path("M17.628 9.389V23.26a1.2 1.2 0 0 1-.742 1.1a1.2 1.2 0 0 1-.45.091H7.027a10 10 0 0 1-.521-.65a12.74 12.74 0 0 1-2.553-7.657v-.286A12.7 12.7 0 0 1 6.05 8.85a9 9 0 0 1 .456-.65h9.93a1.2 1.2 0 0 1 1.192 1.189");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.g8l4hwrvx {
  d: path("M16.977 10.04v13.871a1.2 1.2 0 0 1-.091.448a1.2 1.2 0 0 1-1.1.741H7.62q-.309-.314-.593-.65a10 10 0 0 1-.521-.65a12.74 12.74 0 0 1-2.553-7.657v-.286A12.7 12.7 0 0 1 6.05 8.85h9.735a1.2 1.2 0 0 1 1.192 1.19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h4lu0cl9n {
  d: path("M16.977 10.04v12.571a1.2 1.2 0 0 1-1.192 1.189H6.506a12.74 12.74 0 0 1-2.553-7.657v-.286A12.7 12.7 0 0 1 6.05 8.85h9.735a1.2 1.2 0 0 1 1.192 1.19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ljf15lm1f {
  stop-color: var(--svg-color--ca4c28, #ca4c28);
}

.lugf9nb5a {
  d: path("M3.194 8.85h11.938a1.193 1.193 0 0 1 1.194 1.191v11.918a1.193 1.193 0 0 1-1.194 1.191H3.194A1.19 1.19 0 0 1 2 21.959V10.041A1.19 1.19 0 0 1 3.194 8.85");
}

.u-o_sr-1l {
  stop-color: var(--svg-color--c5401e, #c5401e);
}

.v306jcbxc {
  fill: var(--svg-color--ff8f6b, #ff8f6b);
  d: path("M17.123 3h-.146v13l6.511 2.6L30 16v-.146A12.9 12.9 0 0 0 17.123 3");
}

.w_urqz91r {
  fill: var(--svg-color--d35230, #d35230);
  d: path("M30 16v.143A12.905 12.905 0 0 1 17.12 29h-.287a12.907 12.907 0 0 1-12.88-12.857V16Z");
}

.w842ttblp {
  stop-color: var(--svg-color--b62f14, #b62f14);
}

.xjc2kf1uv {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.293 12.028a3.3 3.3 0 0 1 2.174.636a2.27 2.27 0 0 1 .756 1.841a2.56 2.56 0 0 1-.373 1.376a2.5 2.5 0 0 1-1.059.935a3.6 3.6 0 0 1-1.591.334H7.687v2.8H6.141v-7.922ZM7.686 15.94h1.331a1.74 1.74 0 0 0 1.177-.351a1.3 1.3 0 0 0 .4-1.025q0-1.309-1.525-1.31H7.686z");
}

.xt94p9b6e {
  d: path("M16.326 10.04v12.571a1.2 1.2 0 0 1-1.192 1.189H6.506a12.74 12.74 0 0 1-2.553-7.657v-.286A12.7 12.7 0 0 1 6.05 8.85h9.084a1.2 1.2 0 0 1 1.192 1.19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z612e-6xk {
  fill: var(--svg-color--ed6c47, #ed6c47);
  d: path("M18.93 17.3L16.977 3h-.146A12.9 12.9 0 0 0 3.953 15.854V16Z");
}

</style>
