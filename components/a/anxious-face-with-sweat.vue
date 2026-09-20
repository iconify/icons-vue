<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVG9SzOgJjz" x1="63.79" x2="63.79" y1="65.667" y2="3.276" gradientUnits="userSpaceOnUse"><stop offset="0" class="gd0gtsapz"/><stop offset=".151" class="ytgu838_q"/><stop offset=".473" class="jg22bvwgp"/><stop offset=".935" class="v3br35bqe"/><stop offset="1" class="edl656b9v"/></linearGradient><path fill="url(#SVG9SzOgJjz)" class="zixn6-blk"/><path class="bzumb5b7r"/><path class="f0gip2b8w"/><defs><path id="SVGPHZb3uoh" class="o-nzxcbpg"/></defs><use href="#SVGPHZb3uoh" class="n1mjunbsu"/><clipPath id="SVG9RrlIZcd"><use href="#SVGPHZb3uoh"/></clipPath><path clip-path="url(#SVG9RrlIZcd)" class="qgpm1w60r"/><defs><path id="SVGZuB9udAA" class="jwa-9bbut"/></defs><use href="#SVGZuB9udAA" class="n1mjunbsu"/><clipPath id="SVGpgJGvbsM"><use href="#SVGZuB9udAA"/></clipPath><path clip-path="url(#SVGpgJGvbsM)" class="prmd3j6np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:anxious-face-with-sweat" /></template>
<style>
.bzumb5b7r {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M86.34 90.53c0 13.17-10 18.72-22.34 18.72s-22.34-5.55-22.34-18.72s10-28.96 22.34-28.96s22.34 15.8 22.34 28.96");
}

.edl656b9v {
  stop-color: var(--svg-color--42ade7, #42ade7);
}

.f0gip2b8w {
  fill: var(--svg-color--fff, #fff);
  d: path("M119.4 68.7c-1.51 4.55-4.85 7.13-7.49 7.67c-2.96.59-5.52-.1-7.2-1.95c-2.14-2.33-2.57-6.12-1.24-10.67c2.41-8.17 2.82-22.96 2.83-23.1c.01-.57.35-1.06.89-1.24c.52-.21 1.11-.05 1.49.37c12.9 14.41 12.27 24.3 10.72 28.92");
}

.gd0gtsapz {
  stop-color: var(--svg-color--fcc21b, #fcc21b);
}

.jg22bvwgp {
  stop-color: var(--svg-color--abb973, #abb973);
}

.jwa-9bbut {
  d: path("M70.29 40.71c.29-3.83 1.78-7.26 4.03-9.91c11.8.13 22.02 4.42 26.37 6.55c.46 1.8.66 3.72.51 5.69c-.69 9.15-8.17 16.04-16.7 15.4s-14.89-8.58-14.21-17.73");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o-nzxcbpg {
  d: path("M57.71 40.71c-.29-3.83-1.78-7.26-4.03-9.91c-11.8.13-22.02 4.42-26.37 6.55c-.46 1.8-.66 3.72-.51 5.69c.69 9.15 8.17 16.04 16.7 15.4s14.89-8.58 14.21-17.73");
}

.prmd3j6np {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M73.32 33.48c-.3 3.33 2.36 6.46 5.96 7.01s6.76-1.71 7.07-5.03c.32-3.33-2.35-6.46-5.95-7.01c-3.59-.55-6.77 1.7-7.08 5.03");
}

.qgpm1w60r {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M54.68 33.48c.3 3.33-2.36 6.46-5.96 7.01s-6.76-1.71-7.07-5.03C41.33 32.13 44 29 47.6 28.45c3.59-.55 6.77 1.7 7.08 5.03");
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
