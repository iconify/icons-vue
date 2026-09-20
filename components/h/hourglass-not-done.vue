<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mdzlnmbhl"/><ellipse class="kll8ftbyf"/><ellipse class="dtmgvqbyx"/><path class="jxpq4zbqh"/><path class="i9v6azbjl"/><path class="nnvr4xbkv"/><ellipse class="e2pb5z5ke"/><path class="zsric9i2u"/><path class="d4bqokcrr"/><path class="mhyb46_oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:hourglass-not-done" /></template>
<style>
.d4bqokcrr {
  fill: var(--svg-color--e2a610, #e2a610);
  d: path("M42.37 43.29c5.36 2.77 17.12 6.72 22.92 4.72s28.23-16.01 29-19c.96-3.7-26 5.71-35.49 7.91c-6.43 1.49-18.71.72-21.47 1.3c-2.75.57.11 2.52 5.04 5.07");
}

.dtmgvqbyx {
  cx: 64px;
  cy: 108.48px;
  fill: var(--svg-color--cc8552, #cc8552);
  rx: 40.64px;
  ry: 7.68px;
}

.e2pb5z5ke {
  cx: 64px;
  cy: 10.08px;
  fill: var(--svg-color--cc8552, #cc8552);
  rx: 40.64px;
  ry: 6.08px;
}

.i9v6azbjl {
  fill: var(--svg-color--1d44b3, #1d44b3);
  d: path("m97.46 18.94l-66.98-.08l-.11 4.52S37.62 27.1 64 27.1s33.63-3.72 33.63-3.72z");
  opacity: var(--svg-opacity--0-39, 0.39);
}

.jxpq4zbqh {
  fill: var(--svg-color--81d4fa, #81d4fa);
  d: path("M69.96 65.49c-.75-.31-1.07-.92-1.07-1.73s.25-1.39.98-1.64c4.61-1.86 27.77-10.73 27.77-38.36l-.18-4.82l-66.98-.08l-.12 5.07c0 26.79 23.08 36.25 27.68 38.11c.75.31 1.22.82 1.22 1.73s-.39 1.39-1.13 1.64c-4.61 1.86-27.77 10.73-27.77 38.36a6.95 6.95 0 0 0 5.34 6.5c5.04 1.19 14.38 2.57 30.53 2.57c13.91 0 21.7-1.01 26.03-2.03c3.08-.73 5.29-3.44 5.36-6.6l.01-.61c.01-26.79-23.06-36.25-27.67-38.11");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.kll8ftbyf {
  cx: 64px;
  cy: 108.48px;
  fill: var(--svg-color--ffb17a, #ffb17a);
  rx: 40.64px;
  ry: 7.68px;
}

.mdzlnmbhl {
  fill: var(--svg-color--8b5738, #8b5738);
  d: path("M23.36 116.32v-7.42c7.4-1.9 67.86 0 81.28 0v7.42c0 4.24-18.2 7.68-40.64 7.68s-40.64-3.44-40.64-7.68");
}

.mhyb46_oe {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.79 37.66c1.26 2.94 3.56 9.61.56 10.75c-3 1.15-7.39-3.11-9.47-7.39s-1.89-9.96 1.25-10.05s5.99 2.8 7.66 6.69M42.9 80.6c-3.13 3.66-5.48 8.58-4.59 13.33c.94 5.01 5.6 3.63 7.22 2.36c5.16-4.05 3.75-9.24 7.74-15.07c.68-1 3.52-4.13 3.12-6.1c-.24-1.17-2.96-1.77-7.91.71c-2.18 1.1-3.97 2.9-5.58 4.77");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.nnvr4xbkv {
  fill: var(--svg-color--8b5738, #8b5738);
  d: path("M23.36 17.94v-7.87c7.18-.96 70.91 0 81.28 0v7.87c0 3.36-18.2 6.08-40.64 6.08s-40.64-2.72-40.64-6.08");
}

.zsric9i2u {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M90.59 108.57c.92-.27 1.42-1.31.97-2.16c-3.14-5.94-16.54-6.11-21.61-17.27c-3.38-7.45-3.57-17.81-3.67-22.24c-.14-5.99 2.85-7.28 2.85-7.28c14.16-5.7 24.57-18.86 25.17-30.61c.06-1.17-22.18 9.17-29.83 10.66c-14.14 2.76-28.23-.87-28.31-.37c5.24 11.47 15.79 17.46 22.86 20.32c1.68.69 4.46 3.3 4.37 11.14c-.07 5.61-.77 20.4-10.44 26.69c-3.64 2.37-11.69 5.84-13.19 9.61c-.33.83.14 1.77 1.01 1.99c2.76.7 11.18 1.93 24.27 1.93c10.29.01 20.45-.93 25.55-2.41");
}

</style>
