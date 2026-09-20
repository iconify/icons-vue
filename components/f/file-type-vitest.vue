<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVGTUBgmdJX"><path class="tcewhq8uu"/></mask><g class="ft5dv1b6b"><g mask="url(#SVGTUBgmdJX)" transform="translate(1 6.8)scale(.393)"><path class="h27xtdben"/><g filter="url(#SVGQv8P6csY)"><ellipse transform="rotate(130.6 41.46 10.01)" class="p6hfjc0-o"/></g><g filter="url(#SVGQv8P6csY)"><ellipse transform="rotate(234 18.43 30.5)" class="z523a8bqp"/></g><g filter="url(#SVGQv8P6csY)"><ellipse transform="rotate(23.1 21.94 12.96)" class="ms4ryka2c"/></g><g filter="url(#SVGQv8P6csY)"><ellipse transform="rotate(23.1 56.27 16.72)" class="cobjqpb2u"/></g><g filter="url(#SVGQv8P6csY)"><ellipse transform="rotate(-45 51.35 1.06)" class="rco5plbjo"/></g></g><path class="c4qygkb7b"/><defs><filter id="SVGQv8P6csY" width="4" height="4" x="-2" y="-2" color-interpolation-filters="sRGB"><feGaussianBlur stdDeviation="4.6"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vitest" /></template>
<style>
.c4qygkb7b {
  fill: var(--svg-color--fff, #fff);
  d: path("M3.72 6.8C.1 11.98.08 20 3.72 25.2h2.45c-3.64-5.2-3.62-13.22 0-18.4zm24.56 0h-2.45c3.62 5.18 3.64 13.2 0 18.4h2.45c3.64-5.2 3.62-13.22 0-18.4");
}

.cobjqpb2u {
  cx: 56.27px;
  cy: 16.72px;
  fill: var(--svg-color--03ff00, #03ff00);
  rx: 5.61px;
  ry: 24.53px;
}

.ft5dv1b6b {
  fill: none;
}

.h27xtdben {
  fill: var(--svg-color--00ff74, #00ff74);
  d: path("M0 0h60v44H0z");
}

.ms4ryka2c {
  cx: 21.94px;
  cy: 12.96px;
  fill: var(--svg-color--03ff00, #03ff00);
  rx: 6.37px;
  ry: 5.55px;
}

.p6hfjc0-o {
  cx: 41.46px;
  cy: 10.01px;
  fill: var(--svg-color--00d0c7, #00d0c7);
  rx: 14.03px;
  ry: 3.39px;
}

.rco5plbjo {
  cx: 51.35px;
  cy: 1.06px;
  fill: var(--svg-color--6effe1, #6effe1);
  rx: 4.99px;
  ry: 10.07px;
}

.tcewhq8uu {
  fill: var(--svg-color--fff, #fff);
  d: path("M36.76 42.97c-.33.6-1.1.76-1.65.36L15.96 29.41a1.2 1.2 0 0 1-.46-.92V11.71c0-.93 1.05-1.46 1.8-.92L29 19.31c1.1.8 2.65.46 3.3-.72l9.71-17.25c.2-.35.58-.57.99-.57h15.57c.87 0 1.41.93.99 1.68z");
}

.z523a8bqp {
  cx: 18.43px;
  cy: 30.51px;
  fill: var(--svg-color--00d0c7, #00d0c7);
  rx: 14.03px;
  ry: 6.09px;
}

</style>
